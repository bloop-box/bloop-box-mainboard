# Changelog

## [2.0.1](https://github.com/bloop-box/bloop-box-mainboard/compare/v2.0.0...v2.0.1) (2024-07-31)


### Bug Fixes

* copper edge clearance ([5cf6c49](https://github.com/bloop-box/bloop-box-mainboard/commit/5cf6c498986e1e9f9c909ac74e83c215b622d0d5))

## [2.0.0](https://github.com/bloop-box/bloop-box-mainboard/compare/v1.0.0...v2.0.0) (2023-01-19)


### ⚠ BREAKING CHANGES

* remove HAT EEPROM
* remove I2C level shifter
* remove RGB LED

### Features

* reduce to two layers ([daa27ec](https://github.com/bloop-box/bloop-box-mainboard/commit/daa27ec4ec4a9b25dcfa96f8c26b65ecf9b1ea43))
* remove HAT EEPROM ([cf92000](https://github.com/bloop-box/bloop-box-mainboard/commit/cf92000fae4ed51b5fee4c6e450fc11b1c285ee3))
* remove I2C level shifter ([b94c306](https://github.com/bloop-box/bloop-box-mainboard/commit/b94c306e1bfe5751c49da7d8ca183a51e0bcca7e))
* remove RGB LED ([2c5ac5f](https://github.com/bloop-box/bloop-box-mainboard/commit/2c5ac5f5aaabc408e38f2fca52ec5572b1a649d2))


### Bug Fixes

* change LCSC part number of I2C pullup ([f7b5855](https://github.com/bloop-box/bloop-box-mainboard/commit/f7b5855fdd118c38ff95c6d2ad4129af0cdf2dad))

## 1.0.0 (2023-01-03)


### ⚠ BREAKING CHANGES

* change NFC connector to RC522 pinout

### Features

* add ID EEPROM ([29fca6b](https://github.com/bloop-box/bloop-box-mainboard/commit/29fca6b0ee6d14b70e27916b70edbddad3c6b2fc))
* add initial eeprom settings and append compilation to release workflow ([c9b4758](https://github.com/bloop-box/bloop-box-mainboard/commit/c9b4758c047ae3c0cc543bdbb0cada0100bebeb2))
* add UART to GPIO-Header ([684cdf3](https://github.com/bloop-box/bloop-box-mainboard/commit/684cdf39494faccde475f5c53999123cf644028c))
* change NFC connector to RC522 pinout ([0ccfcac](https://github.com/bloop-box/bloop-box-mainboard/commit/0ccfcacc2717ffdd54632eade2880b5d04bda1c4))
* more variables ([3ad9d62](https://github.com/bloop-box/bloop-box-mainboard/commit/3ad9d622208fb648b1df063b767c59333f17f956))
* prepare files for automatic version numbering ([8c43f3e](https://github.com/bloop-box/bloop-box-mainboard/commit/8c43f3e3125d3cbd04fc097754fc8e28eb9c87ee))
* remove PWM mosfet ([32390eb](https://github.com/bloop-box/bloop-box-mainboard/commit/32390ebd910076f0735f4e2b29f7aa077e36a9bd))
* split mainboard into standalone repository ([22de539](https://github.com/bloop-box/bloop-box-mainboard/commit/22de539663db7e1ce86aedc6387e2e9298a7a61c))


### Bug Fixes

* 3d-model offset for GPIO connector ([8116aa7](https://github.com/bloop-box/bloop-box-mainboard/commit/8116aa759b54e4d8e2731584663043586e68517e))
* add DATE and VERSION text variables ([80477f6](https://github.com/bloop-box/bloop-box-mainboard/commit/80477f68498f7e7a7a6d753b993b55e98668b47b))
* add default connection for I2C voltage jumper ([9834e36](https://github.com/bloop-box/bloop-box-mainboard/commit/9834e3640ebfb245844be0672dab51fcbe79d453))
* remove Tailboard IO protection resistors ([da9ced2](https://github.com/bloop-box/bloop-box-mainboard/commit/da9ced2ef8a0e79e47c1458d0525a38b68af17bd))
* update nets ([658971c](https://github.com/bloop-box/bloop-box-mainboard/commit/658971c0fbd4f4be307cef0f45213d0d53321734))
