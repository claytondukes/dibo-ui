# Core Features

## Character Builder

### Builder Features

The main feature of DIBO UI is the character builder, which allows users to:

* Create and customize Diablo Immortal character builds
* Experiment with different skills, attributes, and gear
* View build statistics and effectiveness
* Compare different build configurations

### Builder Implementation

* Client-side build calculation for instant feedback
* Responsive UI that works on both desktop and mobile
* Clear visualization of build stats and effects
* Progressive enhancement for complex features

## Build Management

### Storage Options

Users can manage their builds in two ways:

* Anonymous (No Login):
  * Create and modify builds
  * Builds stored in local storage
  * No sharing or cross-device access

* GitHub Authentication:
  * All builds saved as GitHub Gists
  * Access builds across devices
  * Share builds via Gist URLs
  * Customize builds generated by the API
  * Maintain a personal build inventory

### Storage Implementation

* Local storage with type-safe persistence
* GitHub Gists integration:
  * Each build saved as a separate Gist
  * Gists contain build configuration and metadata
  * OpenAPI-generated client for API calls
  * Real-time inventory sync

## User Experience

### Core Principles

* No login wall - users can start building immediately
* Progressive enhancement - authentication adds features but isn't required
* Instant feedback - all build calculations happen client-side
* Mobile-first design - fully functional on all devices
* Accessibility - WCAG 2.1 AA compliant

### UX Implementation

* Clean, intuitive interface
* Clear visual feedback for build changes
* Smooth transitions using View Transitions API
* Responsive layout with Tailwind CSS
* Keyboard navigation support

## Technical Features

### Frontend Architecture

* Vite + React 19
* TypeScript 5.3+ with strict mode
* TanStack Query v5 for API state
* Jotai for UI state
* Radix UI for accessible components
* Tailwind CSS 4.0 for styling

### Authentication

* GitHub OAuth integration for:
  * User authentication
  * Gist access and management
* Secure token management
* Clear login/logout flows
* Error boundaries and fallbacks

### API Integration

* OpenAPI-generated TypeScript client
* Automatic request retries
* Proper error handling
* Loading states and optimistic updates
* Real-time data synchronization
