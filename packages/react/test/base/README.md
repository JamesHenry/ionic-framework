# React Test App

## Getting Started

### Setup

Make sure you are using the latest versions of node and npm. If you do not have these, [download the installer](https://nodejs.org/) for the LTS version of Node.js. This is the best way to also [install npm](https://blog.npmjs.org/post/85484771375/how-to-install-npm#_=_).

### Building Dependencies

Ensure that the `core`, `packages/react` and `packages/react-router` directories are built by running the following from the root of the repo:

```bash
npm i
npm run build -w core
npm run build -w packages/react
npm run build -w packages/react-router
```

Then, install dependencies from this directory for this test app:

```
npm i
```

### Previewing App

To preview this app locally, run the following from this directory:

```bash
npm start
```

### Running Tests

To run the e2e tests, run the following from this directory:

```
npm run build
npm run e2e
```
