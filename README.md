# DIBO UI

A modern, responsive web application for character building and management in Diablo
Immortal.

## Tech Stack

* Vite + React 19
* TypeScript 5.3+
* Tailwind CSS 4.0
* Radix UI
* TanStack Query v5
* Jotai

## Getting Started

1. Install dependencies:

   ```bash
   pnpm install
   ```

2. Set up environment variables:

   ```bash
   cp .env.example .env
   ```

3. Run the development server:

   ```bash
   pnpm dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Development

### Project Structure

```text
src/
├── api/              # API integration
├── components/       # UI components
├── hooks/           # Custom React hooks
├── lib/             # Utilities
├── pages/           # Route components
├── store/           # Jotai atoms
└── styles/          # Global styles
```

### Commands

* `pnpm dev` - Start development server
* `pnpm build` - Build production bundle
* `pnpm preview` - Preview production build
* `pnpm lint` - Run ESLint
* `pnpm test` - Run tests
* `pnpm test:e2e` - Run E2E tests

## Contributing

1. Create a new branch:

   ```bash
   git checkout -b feat/your-feature-name
   ```

2. Make your changes following our coding standards
3. Write tests for your changes
4. Commit your changes using conventional commit messages:

   ```bash
   git commit -m "feat: add new feature"
   ```

5. Push your changes and create a pull request

## License

MIT
