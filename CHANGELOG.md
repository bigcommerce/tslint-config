# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

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
