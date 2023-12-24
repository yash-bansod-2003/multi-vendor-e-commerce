# Multi-vendor E-commerce Web App

A Multi-vendor E-commerce Web App, a platform where multiple sellers can showcase and sell their products in one centralized marketplace, offering customers a diverse range of choices.


## What's inside?

Optimize industry-level processes to ensure maintainability, scalability, cleanliness, and adherence to best practices.

### Overview of floder strcture Apps

- `api`: an [Express](https://expressjs.com/) server
- `storefront`: a [Next.js](https://nextjs.org/) app
- `admin`: a [Vite](https://vitejs.dev/) single page app
- `blog`: a [Remix](https://remix.run/) blog
- `@repo/logger`: isomorphic logger (a small wrapper around console.log)
- `@repo/ui`: a dummy React UI library (which contains a single `<CounterButton>` component)
- `scripts`: Jest and ESLint configurations
- `@repo/typescript-config`: tsconfig.json's used throughout the monorepo

Each package and app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

The utilities facilitate an efficient development process and ensure software quality

- [Turborepo](https://turbo.build/repo) for monorepo environment
- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting
- [Shadcn/UI](https://ui.shadcn.com/) for reusable ui component 