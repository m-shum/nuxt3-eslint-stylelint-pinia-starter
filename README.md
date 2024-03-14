# Nuxt 3 Starter

## With eslint, stylelint, pinia, and pre-commit hooks

- Stylelint
- Eslint
- Prettier
- Husky & lint-staged
- Pinia
- Basic directory structure including /components, /layouts, /pages, and /assets
- SCSS
- Engine versioning with nvm

## Make it your own

This repository is set up using npm, however you can edit package.json to use yarn.

It comes with a basic css reset, which can be found in `assets/styles/reset.scss`. Feel free to amend, remove, and use your own!

It's configured with husky and lint-staged to ensure your code stays clean with each commit ✨
It uses @antfu/eslint-config; for more information on how to customise your linting config, visit https://github.com/antfu/eslint-config

To learn more about how to customise your stylelint configuration, visit https://stylelint.io/user-guide/configure/

## Getting Started

### Set your node version with nvm

❗️If you do not already have nvm installed, you can install it here: https://github.com/nvm-sh/nvm

Set the correct engine versions using nvm:

```bash
nvm use
```

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

### Install Dependencies

To install dependencies:

```bash
# npm
npm install
```

### Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev
```

### Production

Build the application for production:

```bash
# npm
npm run build
```

Locally preview production build:

```bash
# npm
npm run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
