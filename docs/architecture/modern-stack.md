# Modern Technical Stack (2025)

## Core Technologies

### Build & Development

1. **Vite**
   * Lightning fast HMR
   * Optimized build performance
   * Rich plugin ecosystem

2. **TypeScript 5.3+**
   * Strict mode enabled
   * Latest ECMAScript features
   * Improved type inference

### UI Framework

1. **React 19**
   * Automatic batching
   * Concurrent features
   * Improved Suspense

2. **Radix UI**
   * WAI-ARIA compliant
   * Composable components
   * Framework agnostic

### Styling

1. **Tailwind CSS 4.0**
   * Just-in-Time compilation
   * Built-in dark mode
   * Custom design tokens

2. **CSS Variables**
   * Dynamic theming
   * Runtime customization

3. **View Transitions API**
   * Smooth page transitions
   * Native performance

### State Management

1. **Jotai**
   * Atomic state management
   * DevTools integration
   * TypeScript-first

2. **TanStack Query v5**
   * Automatic background updates
   * Infinite loading support
   * Suspense integration

### API Integration

1. **OpenAPI TypeScript Generator**
   * Type-safe API calls
   * Runtime validation
   * Automatic client generation

2. **Axios**
   * Request/response interceptors
   * Automatic retries
   * Progress monitoring

### Testing

1. **Vitest**
   * Native ESM support
   * Watch mode
   * Compatible with Jest APIs

2. **Testing Library**
   * User-centric testing
   * Accessibility checks

3. **Playwright**
   * Cross-browser testing
   * Mobile device simulation

4. **MSW**
   * Network-level mocking
   * REST/GraphQL support

### Development Tools

1. **pnpm**
   * Disk space efficient
   * Strict dependency resolution
   * Workspace support

2. **ESLint**
   * TypeScript support
   * React hooks rules
   * Import sorting

3. **Prettier**
   * Consistent style
   * Editor integration

## Project Structure

```text
src/
├── api/              # API integration
│   ├── client.ts     # API client setup
│   └── types/        # Generated types
├── components/       # UI components
│   ├── ui/          # Base components
│   └── features/    # Feature components
├── hooks/           # Custom React hooks
├── lib/             # Utilities
├── pages/           # Route components
├── store/           # Jotai atoms
└── styles/          # Global styles
```

## Development Workflow

### Local Development

1. Install dependencies:

   ```bash
   pnpm install
   ```

2. Start dev server:

   ```bash
   pnpm dev
   ```

3. Run tests:

   ```bash
   pnpm test
   ```

### Build & Deploy

1. Type check:

   ```bash
   pnpm type-check
   ```

2. Build:

   ```bash
   pnpm build
   ```

3. Preview:

   ```bash
   pnpm preview
   ```

### Code Quality

* Pre-commit hooks for linting and formatting
* Automated testing on PR
* Bundle size monitoring
* Performance budgets

## Performance Optimization

### Build Time

* Code splitting
* Tree shaking
* Asset optimization
* Module federation

### Runtime

* Component lazy loading
* Image optimization
* Font optimization
* Cache strategies

### Monitoring

* Web Vitals tracking
* Error boundary reporting
* Performance monitoring
* User analytics
