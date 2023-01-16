# Vitae

Vitae is an opinionated starter template that uses Vite + React + Typescript

## Features

- Coding: [Vite](https://vitejs.dev) with [SWC](https://swc.rs/) + [React](https://reactjs.org) with [TypeScript](https://www.typescriptlang.org).
- Styling: [Tailwind](https://tailwindcss.com) + [Prettier plugin](https://github.com/tailwindlabs/prettier-plugin-tailwindcss).
- Linting: [ESLint](https://eslint.org), [stylelint](https://stylelint.io) and [Prettier](https://prettier.io) and [Husky](https://github.com/typicode/husky) + [lint-staged](https://github.com/okonet/lint-staged) + [commitlint](https://commitlint.js.org/#/) to lint before commits .
- Testing: Unit testing with [Vitest](https://vitest.dev/) + [Testing Library](https://testing-library.com/) and E2E testing with [Playwright](https://playwright.dev/).
- GitHub Actions for automatic unit & e2e test running.

## Getting started

Use this repository as a [GitHub template](https://https://github.com/LuisVallespin/Vitae/generate):

Then, install the dependencies:

```
npm i
```

### Before you start coding

- [ ] Change the `name` field in package.json.
- [ ] Not interested in GitHub Actions? Delete the `.github` folder.
- [ ] Modify or delete the `LICENSE` file.

## Scripts

- `npm dev` - start a development server with hot reload.
- `npm build` - generate the build for production on the `dist` folder.
- `npm format` - format all files with Prettier.
- `npm preview` - preview the production build.
- `npm prepare` - prepares the project to use Husky.
- `npm test` - run all the unit tests with Vitest.
- `npm e2e` - run all e2e tests using Playwright.
- `npm lint` - runs ESLint and Stylelint.
- `npm format` - format all files with Prettier.
