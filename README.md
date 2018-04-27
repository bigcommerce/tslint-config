# @bigcommerce/tslint-config


This package is a configuration preset for [TSLint](https://palantir.github.io/tslint). It contains a set of rules applied to most TypeScript projects at BigCommerce.


## Install

```sh
npm install --save-dev @bigcommerce/tslint-config
```


## Usage

Add `@bigcommerce/tslint-config` to your project's TSLint configuration file. i.e.:

```json
{
    "extends": "@bigcommerce/tslint-config"
}
```

If possible, try not to override the preset unless you have a special reason.


## Release

To release:

```sh
npm run release
```

Please refer to the documentation of [standard-version](https://github.com/conventional-changelog/standard-version) for more options.


## License

MIT
