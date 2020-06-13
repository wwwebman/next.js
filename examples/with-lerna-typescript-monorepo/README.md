# Lerna monorepo for Typescript codebase

The example shows how you can manage monorepo using [Lerna](https://github.com/lerna/lerna) monorepo package managing tool.
In this example you can figure out how to:

- Setup Lerna for [Typescript](https://www.typescriptlang.org/) codebase
- Setup custom aliases on the server and the client
- Make aliases work together with [Jest](https://jestjs.io/)

Monorepo consists of 3 packages:

- [@project/app](./packages/app)
- [@project/utils](./packages/utils)
- [@project/ui](./packages/ui)

## How to use

### Using `create-next-app`

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example with-lerna-typescript-monorepo with-lerna-typescript-monorepo-app
# or
yarn create next-app --example with-lerna-typescript-monorepo with-lerna-typescript-monorepo-app
```

### Download manually

Download the example:

```bash
curl https://codeload.github.com/vercel/next.js/tar.gz/canary | tar -xz --strip=2 next.js-canary/examples/with-lerna-typescript-monorepo
cd with-lerna-typescript-monorepo
```

Install it and run:

Development:

```bash
yarn
cd packages/app
yarn dev
```

Production:

```bash
yarn
yarn app:build
cd packages/app
yarn start
```
