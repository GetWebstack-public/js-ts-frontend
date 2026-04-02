# js-ts-frontend — Hello World Templates

A set of ready-to-run "Hello World" frontend templates for the most popular JavaScript and TypeScript frameworks. Each template is a standalone starting point: **fork the one you want, run it with `gws`, and start building**.

## Available Templates

| Template | Language | Framework |
|----------|----------|-----------|
| [angular-ssr](./angular-ssr) | TypeScript | [Angular](https://angular.dev/) (SSR) |
| [astro](./astro) | TypeScript | [Astro](https://astro.build/) |
| [gatsby](./gatsby) | JavaScript | [Gatsby](https://www.gatsbyjs.com/) |
| [nextjs-app-router](./nextjs-app-router) | TypeScript | [Next.js](https://nextjs.org/) (App Router) |
| [nextjs-pages](./nextjs-pages) | TypeScript | [Next.js](https://nextjs.org/) (Pages Router) |
| [nuxt3](./nuxt3) | TypeScript | [Nuxt](https://nuxt.com/) |
| [preact](./preact) | JavaScript | [Preact](https://preactjs.com/) |
| [qwik](./qwik) | TypeScript | [Qwik](https://qwik.dev/) |
| [react-cra](./react-cra) | JavaScript | [React](https://react.dev/) (Create React App) |
| [react-vite](./react-vite) | JavaScript | [React](https://react.dev/) (Vite) |
| [remix](./remix) | TypeScript | [Remix](https://remix.run/) |
| [solid-vite](./solid-vite) | JavaScript | [Solid.js](https://www.solidjs.com/) |
| [svelte-standalone](./svelte-standalone) | JavaScript | [Svelte](https://svelte.dev/) |
| [sveltekit](./sveltekit) | TypeScript | [SvelteKit](https://kit.svelte.dev/) |
| [vue3-vite](./vue3-vite) | JavaScript | [Vue](https://vuejs.org/) |

## Getting Started

### 1. Create a GetWebstack account

Sign up for a free account at [app.getwebstack.com](https://app.getwebstack.com). You'll need it to initialise and manage your projects with the `gws` CLI.

### 2. Pick a template and fork it

Browse the templates above, choose the framework you want to work with, and fork that repository into your own GitHub account.

### 3. Install the GetWebstack CLI

```bash
curl -sSL https://getwebstack.com/install.sh | bash
```

### 4. Log in to GetWebstack

```bash
gws login
```

This authenticates the CLI with your GetWebstack account.

### 5. Initialise the project

Inside the forked project directory, run:

```bash
gws init
```

This discovers the application and generates the necessary configuration files to run it locally.

### 6. Start the application

```bash
gws up
```

This builds the application and starts it in a local Kubernetes cluster. Each template returns a simple `Hello World` response to confirm everything is working.

### 7. Start developing

The templates are intentionally minimal — just enough to get a working application running. Add pages, components, API routes, and anything else your project needs.

> Some templates require secrets (e.g. API keys) to be configured in the GetWebstack app before running. Check the template's own `README.md` for any additional setup steps.

## Fullstack Templates

Looking for a frontend + backend starting point? Check out the fullstack templates:

| Template | Description |
|----------|-------------|
| [react-express-multi-repo](https://github.com/GetWebstack-public/react-express-multi-repo) | React frontend with an Express backend |

## Other Template Collections

| Collection | Description |
|------------|-------------|
| [js-ts-backend](https://github.com/GetWebstack-public/js-ts-backend) | Hello World templates for JavaScript and TypeScript backends |
| [go-projects](https://github.com/GetWebstack-public/go-projects) | Hello World templates for Go backends |
| [python-projects](https://github.com/GetWebstack-public/python-projects) | Hello World templates for Python backends |
