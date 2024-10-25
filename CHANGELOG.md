# Changelog

## [0.4.0](https://github.com/olehmisar/noir-bignum/compare/v0.3.5...v0.4.0) (2024-10-25)


### ⚠ BREAKING CHANGES

* refactor library architecture ([#36](https://github.com/olehmisar/noir-bignum/issues/36))
* bump minimum noir version to 0.35.0 and address privacy warnings #24

### Features

* Added modular square root computation and fully constrained `derive_from_seed` method ([#32](https://github.com/olehmisar/noir-bignum/issues/32)) ([20e03b0](https://github.com/olehmisar/noir-bignum/commit/20e03b04f7e2c57b61538d707695ae02979c51b4))
* Bignum uses generic arithmetic instead of clunky ArrayX struct ([#17](https://github.com/olehmisar/noir-bignum/issues/17)) ([08f5710](https://github.com/olehmisar/noir-bignum/commit/08f5710e085e55c038b8555032c90a31d7c91037))
* Bls12-381-fr params ([8133bba](https://github.com/olehmisar/noir-bignum/commit/8133bba56c67707c3abdf0186fdff6d0658eec4d))
* Refactor library architecture ([#36](https://github.com/olehmisar/noir-bignum/issues/36)) ([4fa65f6](https://github.com/olehmisar/noir-bignum/commit/4fa65f6be596ea1b6c6c49b784fa7a9aca95c5d4))


### Bug Fixes

* Bump minimum noir version to 0.35.0 and address privacy warnings [#24](https://github.com/olehmisar/noir-bignum/issues/24) ([fc53098](https://github.com/olehmisar/noir-bignum/commit/fc53098332e1843759114ad7c05118e8fee141ed))
* Fixed reduction parameter error ([#31](https://github.com/olehmisar/noir-bignum/issues/31)) ([c312ef7](https://github.com/olehmisar/noir-bignum/commit/c312ef72e2127153fad5afcffc5bf88045a5b4ba))
* From_bytes_be ([9ee587d](https://github.com/olehmisar/noir-bignum/commit/9ee587d95c4b992b939ce8b0d56b458078d8203d))
* Issue with bit check in `from_be_bytes` ([1df2767](https://github.com/olehmisar/noir-bignum/commit/1df2767c3f1217a3d4a38ad3479897364591f5f7))
* Remove function which was ignoring compiler warning to not do that ([#21](https://github.com/olehmisar/noir-bignum/issues/21)) ([bb348ac](https://github.com/olehmisar/noir-bignum/commit/bb348ac607236f7fb8dab75bef557cc2a23cf408))
* Remove unnecessary generic from `ArrayX.__normalize_limbs()` ([b5afd7b](https://github.com/olehmisar/noir-bignum/commit/b5afd7b65b9e93a6932a1d9ae33cdc4472212db3))
* Update to use new `to_le_bytes` ([fa8d20c](https://github.com/olehmisar/noir-bignum/commit/fa8d20cead061acf516cba96dd6123c0c60f6a66))
* Workaround shifts to compile with latest noir ([75d10a4](https://github.com/olehmisar/noir-bignum/commit/75d10a4916d85e713fb895c414b489be46f68034))

## [0.3.5](https://github.com/noir-lang/noir-bignum/compare/v0.3.4...v0.3.5) (2024-10-02)


### Features

* Bignum uses generic arithmetic instead of clunky ArrayX struct ([#17](https://github.com/noir-lang/noir-bignum/issues/17)) ([08f5710](https://github.com/noir-lang/noir-bignum/commit/08f5710e085e55c038b8555032c90a31d7c91037))
