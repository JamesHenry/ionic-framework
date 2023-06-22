# @ionic/vue

Ionic Framework integration for Vue 3 apps.

## Building

1. Install dependencies from the root of the repo:

```shell
npm install
```

2. Build `@ionic/core`:

- Either by running it from the root with `npm run build -w core`
- Or by changing directory into core and then running its build:

```shell
cd core
npm run build
```

This will generate Vue component bindings in the `packages/vue` directory.

3. Build `@ionic/vue`:

- Either by running it from the root with `npm run build -w packages/vue`
- Or by changing directory into `packages/vue` and then running its build:

```shell
cd packages/vue
npm run build
```

## Tests

* E2E Tests are found in the `packages/vue/test-app/tests` directory and use Cypress.
* When making changes to `@ionic/vue` or `@ionic/vue-router` you can run `npm run sync` in the `test-app` directory to ensure that the test application is using your built changes. Be sure to build in the `vue` and `vue-router` directories first.
* Tests can be run in headless mode by running `npm run cypress`.
* If you want to open the Cypress test runner, you can run `node_modules/.bin/cypress open`.
* Bug fix and feature PRs should have new tests verifying the PR functionality.

## Contributing

See our [Contributing Guide](https://github.com/ionic-team/ionic-framework/blob/main/.github/CONTRIBUTING.md).

## Need Help?

Post your question on the [Ionic Forum](http://forum.ionicframework.com/).