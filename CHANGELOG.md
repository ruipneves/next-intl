# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [3.1.1](https://github.com/moxystudio/next-intl/compare/v3.1.0...v3.1.1) (2022-04-01)

## [3.1.0](https://github.com/moxystudio/next-intl/compare/v3.0.2...v3.1.0) (2021-06-24)


### Features

* add next 11 compat ([921bd03](https://github.com/moxystudio/next-intl/commit/921bd034f39ed539816c6c1e4cd1fb2113fec95a))

### [3.0.2](https://github.com/moxystudio/next-intl/compare/v3.0.1...v3.0.2) (2021-04-24)


### Bug Fixes

* do not use __NEXT_DATA__ ([dbd2eae](https://github.com/moxystudio/next-intl/commit/dbd2eaeea5b7d8c8d4e7a3a4f572739aa6a862ac))

### [3.0.1](https://github.com/moxystudio/next-intl/compare/v3.0.0...v3.0.1) (2021-04-18)


### Bug Fixes

* behave well when rendering _error page ([7f63cad](https://github.com/moxystudio/next-intl/commit/7f63cad28db0239ede7171cd937d50b717484f0d))
* do not crash if __NEXT_DATA__ is not defined ([7e97277](https://github.com/moxystudio/next-intl/commit/7e97277b33b8fb123671359c150e1cb6e4490d4c))

## [3.0.0](https://github.com/moxystudio/next-intl/compare/v2.4.1...v3.0.0) (2021-04-17)


### ⚠ BREAKING CHANGES

* The setup has changed, please follow the new guide.
* Polyfills are not automatically loaded anymore.
* Next.js >= v10 is now required.

### Features

* upgrade to use Next.js new i18n capabilities ([1e572ca](https://github.com/moxystudio/next-intl/commit/1e572ca6b67b61188ddf5a7a2148bb4f16829722))

### [2.4.1](https://github.com/moxystudio/next-intl/compare/v2.4.0...v2.4.1) (2021-03-23)

## [2.4.0](https://github.com/moxystudio/next-intl/compare/v2.3.0...v2.4.0) (2021-01-18)


### Features

* load polyfills individually if needed ([bc1fba4](https://github.com/moxystudio/next-intl/commit/bc1fba4a69329597556757499373eb2e38d9b103))

## [2.3.0](https://github.com/moxystudio/next-intl/compare/v2.2.1...v2.3.0) (2021-01-18)


### Features

* next 10 compat ([041b25e](https://github.com/moxystudio/next-intl/commit/041b25e07f772d2230e55e17793225eccea2c7af))


### Bug Fixes

* fix error message extra quote ([b58e76a](https://github.com/moxystudio/next-intl/commit/b58e76a4e0788d4e4c64838155ebd5455ee2c210))

### [2.2.1](https://github.com/moxystudio/next-intl/compare/v2.2.0...v2.2.1) (2020-09-01)


### Bug Fixes

* fix hot-update json being recognized as a data request ([#17](https://github.com/moxystudio/next-intl/issues/17)) ([ab62674](https://github.com/moxystudio/next-intl/commit/ab62674b12387d0d342ed554c87727df061caea0))

## [2.2.0](https://github.com/moxystudio/next-intl/compare/v2.1.1...v2.2.0) (2020-08-28)


### Features

* improve performance when pages are using getServerSideProps ([0758392](https://github.com/moxystudio/next-intl/commit/075839242fb28812a6dc721ce9180fe3fe78ad3e))

### [2.1.1](https://github.com/moxystudio/next-intl/compare/v2.1.0...v2.1.1) (2020-08-17)


### Bug Fixes

* fix withNextIntlSetup not working purely client-side ([049ae94](https://github.com/moxystudio/next-intl/commit/049ae9419bffa3f6782ac7e3287e185d66bb6318))

## [2.1.0](https://github.com/moxystudio/next-intl/compare/v2.0.3...v2.1.0) (2020-08-07)


### Features

* support react-intl v5 ([8f84e90](https://github.com/moxystudio/next-intl/commit/8f84e90be8177b4bf40774010b448987b4c5b199))

### [2.0.3](https://github.com/moxystudio/next-intl/compare/v2.0.2...v2.0.3) (2020-08-07)


### Bug Fixes

* fix integration with recent Next.js versions ([7e0e338](https://github.com/moxystudio/next-intl/commit/7e0e338c7f15d71f879068a6bffa987cf35727a6))

### [2.0.2](https://github.com/moxystudio/next-intl/compare/v2.0.1...v2.0.2) (2020-04-30)


### Bug Fixes

* clientDeferred catch is not a function error ([#13](https://github.com/moxystudio/next-intl/issues/13)) ([11e4418](https://github.com/moxystudio/next-intl/commit/11e44187abe16a020db12919877055f291a0f245))

### [2.0.1](https://github.com/moxystudio/next-intl/compare/v2.0.0...v2.0.1) (2020-04-02)


### Bug Fixes

* surpress unhandled promise error ([4e39c5e](https://github.com/moxystudio/next-intl/commit/4e39c5ea091b0110360b8e85e6a1e7f2c169c277))

## [2.0.0](https://github.com/moxystudio/next-intl/compare/v1.1.11...v2.0.0) (2020-03-06)


### ⚠ BREAKING CHANGES

* react-intl v3 is no longer supported

### Features

* upgrade to react-intl v4 ([#11](https://github.com/moxystudio/next-intl/issues/11)) ([d27f85d](https://github.com/moxystudio/next-intl/commit/d27f85d8fce249b2657bdf795d0b42ab683914c7))

## [1.2.0](https://github.com/moxystudio/next-intl/compare/v1.1.11...v1.2.0) (2020-03-06)


### Features

* upgrade to react-intl v4 ([#11](https://github.com/moxystudio/next-intl/issues/11)) ([56f0903](https://github.com/moxystudio/next-intl/commit/56f09031b89938e60ce43d0d86cb641a3abac74b))

### [1.1.11](https://github.com/moxystudio/next-intl/compare/v1.1.10...v1.1.11) (2020-02-14)


### Bug Fixes

* fix page getInitialProps not being called ([d3ab91f](https://github.com/moxystudio/next-intl/commit/d3ab91f21e91c03b60fdbb3d83e73231acada843))

### [1.1.10](https://github.com/moxystudio/next-intl/compare/v1.1.9...v1.1.10) (2020-02-04)


### Bug Fixes

* initial props not staying persistent after first render ([eea9661](https://github.com/moxystudio/next-intl/commit/eea9661a6f9d5ef18738215d66a74b45558524e0))

### [1.1.9](https://github.com/moxystudio/next-intl/compare/v1.1.8...v1.1.9) (2020-02-04)


### Bug Fixes

* fix initialData being required ([092f2ab](https://github.com/moxystudio/next-intl/commit/092f2abb00813b0d53cde12df7257415b98a146b))
* fix order of props spreading in hoc ([a8c106c](https://github.com/moxystudio/next-intl/commit/a8c106c5b0fe32d874fc4e7031b7e908b09e7912))

### [1.1.8](https://github.com/moxystudio/next-intl/compare/v1.1.7...v1.1.8) (2020-01-22)


### Bug Fixes

* add to compilation error instead of throwing ([409bdda](https://github.com/moxystudio/next-intl/commit/409bddad8557164040d3dc09578e17eca0d9dd90))

### [1.1.7](https://github.com/moxystudio/next-intl/compare/v1.1.6...v1.1.7) (2020-01-18)


### Bug Fixes

* fix NextIntlWebpackPlugin hanging on client errors ([e426394](https://github.com/moxystudio/next-intl/commit/e4263948cbb706dc219449154ee8f4b47e259380))

### [1.1.6](https://github.com/moxystudio/next-intl/compare/v1.1.5...v1.1.6) (2020-01-07)

### [1.1.5](https://github.com/moxystudio/next-intl/compare/v1.1.4...v1.1.5) (2020-01-07)


### Bug Fixes

* change locales, policies & initialData of the provider to required ([#9](https://github.com/moxystudio/next-intl/issues/9)) ([8fbe363](https://github.com/moxystudio/next-intl/commit/8fbe3636a8cbf6df899d2210072830c4b4237a20))

### [1.1.4](https://github.com/moxystudio/next-intl/compare/v1.1.3...v1.1.4) (2019-12-09)


### Bug Fixes

* change depth to 1 to circuvent an error on some CI runners ([8da98e0](https://github.com/moxystudio/next-intl/commit/8da98e0297e0ed77fe1eadc262222b09b606f6a3))
* fix typo on useNextIntl() section ([#5](https://github.com/moxystudio/next-intl/issues/5)) ([b156440](https://github.com/moxystudio/next-intl/commit/b156440856234ddad55c5bc95834a9e35ef995db))
* fix withNextIntl HOC example ([#6](https://github.com/moxystudio/next-intl/issues/6)) ([542e3b5](https://github.com/moxystudio/next-intl/commit/542e3b5dbe04cb5251b9bf4314e5280877c53d8a))

### [1.1.3](https://github.com/moxystudio/next-intl/compare/v1.1.2...v1.1.3) (2019-11-30)


### Bug Fixes

* make it work even if the .next folder is not deleted ([f59815c](https://github.com/moxystudio/next-intl/commit/f59815cc816e240ad28b9c8b35b2634cea3a8ea2))

### [1.1.2](https://github.com/moxystudio/next-intl/compare/v1.1.1...v1.1.2) (2019-11-30)


### Bug Fixes

* forgot to detect BroadcastChannel when saving cookie ([ec36e64](https://github.com/moxystudio/next-intl/commit/ec36e64fcbfdbf180c71a1782e1c4a3da1dd339d))
* make it work when target is serverless ([05e1c62](https://github.com/moxystudio/next-intl/commit/05e1c62e29af9767a583264b8921eeb36633a5f8))

### [1.1.1](https://github.com/moxystudio/next-intl/compare/v1.1.0...v1.1.1) (2019-11-26)


### Bug Fixes

* declare next as a peer dependency ([ba9d487](https://github.com/moxystudio/next-intl/commit/ba9d487fba96ef2c2323d616c2085e8f0b95d86c))

## [1.1.0](https://github.com/moxystudio/next-intl/compare/v1.0.0...v1.1.0) (2019-11-22)


### Features

* add next plugin that deals with webpack workarounds ([#4](https://github.com/moxystudio/next-intl/issues/4)) ([fa44f95](https://github.com/moxystudio/next-intl/commit/fa44f956409d4349afcfaaebcda2e2d5d0f783a9))

## 1.0.0 (2019-11-20)
