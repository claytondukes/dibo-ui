# Authentication Architecture

## Overview

DIBO UI uses GitHub OAuth for authentication, primarily to enable users to save and share their builds using GitHub Gists. Authentication is optional - users can create and experiment with builds without logging in.

## Authentication Flow

### Anonymous Usage

- Users can access all build creation features without authentication
- Builds are stored in local storage
- No API calls are made for unauthenticated users

### GitHub OAuth (Optional)

When a user chooses to authenticate:

1. User clicks "Login with GitHub"
2. User is redirected to GitHub OAuth page
3. After approval, GitHub redirects back with a code
4. Backend exchanges code for access token
5. User session is established
6. Local builds are converted to Gists (if any)

## Technical Implementation

### Components

- `AuthProvider`: Context provider for auth state
- `LoginButton`: Initiates GitHub OAuth flow
- `AuthGuard`: Protects routes that require authentication
- `GistManager`: Handles Gist operations for builds

### State Management

- Auth state stored in Zustand store
- Token management handled by auth service
- Gist operations managed by dedicated service
- Build synchronization between local storage and Gists

### Security

- No sensitive data stored client-side
- Tokens stored securely in HTTP-only cookies
- CSRF protection via state parameter
- Proper error handling for auth failures
- Secure Gist access and management

## API Integration

### Endpoints

- `/auth/github/login`: Get GitHub OAuth URL
- `/auth/github/callback`: Handle OAuth callback
- `/auth/logout`: Clear session
- `/auth/gists`: CRUD operations for builds
- `/auth/inventory`: Get user's DIBO inventory from gists

### Error Handling

- Network errors
- Invalid tokens
- Expired sessions
- OAuth failures
- Gist operation failures

## User Experience

### Design Principles

- Authentication is optional and non-intrusive
- Clear feedback during auth process
- Smooth transition between states
- Proper error messaging
- No data loss during auth flow
- Seamless build management with Gists
