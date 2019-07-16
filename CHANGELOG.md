# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="4.0.1"></a>
## [4.0.1](https://github.com/bigcommerce/tslint-config/compare/v4.0.0...v4.0.1) (2019-07-16)


### Bug Fixes

* **common:** CHECKOUT-4136 Exclude json files no matter where tslint is placed ([67f6a93](https://github.com/bigcommerce/tslint-config/commit/67f6a93))



<a name="4.0.0"></a>
# [4.0.0](https://github.com/bigcommerce/tslint-config/compare/v3.0.2...v4.0.0) (2019-07-09)


### Bug Fixes

* **common:** CHECKOUT-4231 Remove preblock because it requires an empty spaces for empty objects ([36002c6](https://github.com/bigcommerce/tslint-config/commit/36002c6))
* **common:** FE-40 Prevent tslint from processing json files ([f01995a](https://github.com/bigcommerce/tslint-config/commit/f01995a))


### Features

* **common:** CHECKOUT-4231 Add more whitespace checking ([3fd08ed](https://github.com/bigcommerce/tslint-config/commit/3fd08ed))
* **common:** CHECKOUT-4231 Add no-async-without-await ([beeeff4](https://github.com/bigcommerce/tslint-config/commit/beeeff4))
* **common:** CHECKOUT-4231 Enable no-duplicate-imports ([922b1ad](https://github.com/bigcommerce/tslint-config/commit/922b1ad))
* **common:** CHECKOUT-4231 Enforce `;` as the type terminator ([c489bc9](https://github.com/bigcommerce/tslint-config/commit/c489bc9))



<a name="3.0.2"></a>
## [3.0.2](https://github.com/bigcommerce/tslint-config/compare/v3.0.1...v3.0.2) (2019-01-20)


### Bug Fixes

* **common:** FE-33 Remove no-unused-variable since it is deprecated ([be050d2](https://github.com/bigcommerce/tslint-config/commit/be050d2))



<a name="3.0.1"></a>
## [3.0.1](https://github.com/bigcommerce/tslint-config/compare/v3.0.0...v3.0.1) (2018-12-16)


### Bug Fixes

* **core:** CHECKOUT-3790 Make sure trailing comma is ES compliant ([b5cc2ce](https://github.com/bigcommerce/tslint-config/commit/b5cc2ce))



<a name="3.0.0"></a>
# [3.0.0](https://github.com/bigcommerce/tslint-config/compare/v2.0.2...v3.0.0) (2018-11-30)


### Features

* **core:** CHECKOUT-3079 Enable `no-non-null-assertion` rule ([7d4fde1](https://github.com/bigcommerce/tslint-config/commit/7d4fde1))


### BREAKING CHANGES

* **core:** Using `!` assertion is now considered to be an error.



<a name="2.0.2"></a>
## [2.0.2](https://github.com/bigcommerce/tslint-config/compare/v2.0.1...v2.0.2) (2018-06-20)


### Bug Fixes

* **common:** MERC-3598 Allow tagged template literals ([d2ad2e0](https://github.com/bigcommerce/tslint-config/commit/d2ad2e0))



<a name="2.0.1"></a>
## [2.0.1](https://github.com/bigcommerce/tslint-config/compare/v2.0.0...v2.0.1) (2018-04-27)



<a name="2.0.0"></a>
# [2.0.0](https://github.com/bigcommerce/tslint-config/compare/v1.0.0...v2.0.0) (2018-04-22)


### Features

* **core:** CHECKOUT-3079 Enable `cyclomatic-complexity` rule ([f5f7081](https://github.com/bigcommerce/tslint-config/commit/f5f7081))
* **core:** CHECKOUT-3079 Enable `match-default-export-name` rule ([1483d14](https://github.com/bigcommerce/tslint-config/commit/1483d14))
* **core:** CHECKOUT-3079 Enable `newline-before-return` rule ([f2b409c](https://github.com/bigcommerce/tslint-config/commit/f2b409c))
* **core:** CHECKOUT-3079 Enable `newline-per-chained-call` rule ([832fb26](https://github.com/bigcommerce/tslint-config/commit/832fb26))
* **core:** CHECKOUT-3079 Enable `no-used-variable` rule ([bf74ca3](https://github.com/bigcommerce/tslint-config/commit/bf74ca3))
* **core:** CHECKOUT-3079 Enable `prefer-method-signature` rule ([4461478](https://github.com/bigcommerce/tslint-config/commit/4461478))
* **core:** CHECKOUT-3092 Enable `no-unnecessary-type-assertion` rule ([d9ebe2e](https://github.com/bigcommerce/tslint-config/commit/d9ebe2e))


### BREAKING CHANGES

* **core:** Default modules must be imported and exported with the
same name.
* **core:** Throw an error if there is an unnecessary type assertion.
* **core:** You must now define methods as `foo(): void` in
interfaces and types.
* **core:** You must now have a blank line before any `return` statement.
* **core:** You must now remove all unused variables.
* **core:** Chained method calls now need to be broken apart onto
separate lines.
* **core:** Your linter now complains if your code exceeds the
cyclomatic complexity threshold.



<a name="1.0.0"></a>
# 1.0.0 (2018-04-12)


### Features

* **core:** CHECKOUT-3079 Extract TSLint recommended preset into standalone file ([6b6a641](https://github.com/bigcommerce/tslint-config/commit/6b6a641))
