# ie11-vuetify-symbol-error-vue-cli

This repository is a reproduction of the ie11 issue with vuetify ripple directive and core-js symbol polyfill.

The issue is documented as [known caveat of core-js symbol polyfill](https://github.com/zloirock/core-js#caveats-when-using-symbol-polyfill).

## Steps

1. Install dependencies
2. Start the project with `serve`
3. Open ie11 and go to app url
4. Open devtools/console
5. Click at `Latest Release` button at top right of view
6. Check console. You will see `SCRIPT28 error` in console

## Project setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn serve
```

### Compiles and minifies for production

```
yarn build
```

### Lints and fixes files

```
yarn lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
