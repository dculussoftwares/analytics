# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.2.0 (2023-07-23)


### Bug Fixes

* [#85](https://github.com/DavidWells/analytics/issues/85) ([8b1bc3d](https://github.com/DavidWells/analytics/commit/8b1bc3d322a8281655da536b4f48a1bdaf3616e9))
* missing loadPlugin [#283](https://github.com/DavidWells/analytics/issues/283) ([40035c8](https://github.com/DavidWells/analytics/commit/40035c813886eb0bcafd9ba636da18987810f19d))
* pass options to segment track call. Close [#108](https://github.com/DavidWells/analytics/issues/108) ([5430775](https://github.com/DavidWells/analytics/commit/5430775db5548402ebff5cc13d65bb99b7c2f323))
* segment plugin src match ([1ee2326](https://github.com/DavidWells/analytics/commit/1ee2326cdc33fc750a4d24c39f0784d223ca9a81)), closes [#88](https://github.com/DavidWells/analytics/issues/88)
* set name on page call with title by default or props.name ([69da370](https://github.com/DavidWells/analytics/commit/69da3706eb43d4aad6b61d6216144e4579fb8457))
* **segment-plugin:** fix race condition for analytics.js reading id from localstorage for .page calls ([08e9b7a](https://github.com/DavidWells/analytics/commit/08e9b7a4f5a789ee552b06d2189eaed87510bb00))


### Features

* add .group to segment plugin ([f01da4b](https://github.com/DavidWells/analytics/commit/f01da4bbfb69c1267feb3f9fe3909b8ef504bace))
* add integrations config option to segment ([03d1e41](https://github.com/DavidWells/analytics/commit/03d1e412698dc8bc92d1ebab4460ac3bd45274ca))
* add support for multiple users using same client to pinpoint ([a6e6fba](https://github.com/DavidWells/analytics/commit/a6e6fbae3270c2e9778bea8fbcb831b2282a0ddb))
* **customerio:** Add node version for customerio plugin ([81bd120](https://github.com/DavidWells/analytics/commit/81bd12025b94ba01d062dc27b96ab54ee6f6afe0))
* **plugin-segment:** add segment plugin ([41c7705](https://github.com/DavidWells/analytics/commit/41c77058edd1f3886a2734b6546d0ca560f1948b))
* **segment:** add anonymous id sync ([13fd69e](https://github.com/DavidWells/analytics/commit/13fd69ee02b3f71f00ffa84fae545b421ca137ab))
* **segment:** add serverside implementation ([57b1674](https://github.com/DavidWells/analytics/commit/57b1674098a5dd5b1a8987c3ba8ee0421b1f1959))
* **segment:** add syncAnonymousId setting ([4655845](https://github.com/DavidWells/analytics/commit/4655845a2f62d395c9f12f98d2a58d86ab39d64b))
* **segment:** clear all localstorage on analytics.reset() ([ff9886e](https://github.com/DavidWells/analytics/commit/ff9886ef4f7fe1a75f3f9bdb21ca557226866386))
* **segment:** update disableAnonTracking via bootstrap listener ([7eef8c9](https://github.com/DavidWells/analytics/commit/7eef8c96d993e0f288bd631cdfc1871f4dc1ad2d))
* **segment-plugin:** Add disableAnonymousTraffic options ([85322b7](https://github.com/DavidWells/analytics/commit/85322b70300cb5bdb04cf82a6f44c45e5aa23d95))





## [1.1.4](https://github.com/DavidWells/analytics/compare/@analytics/segment@1.1.3...@analytics/segment@1.1.4) (2022-11-09)


### Bug Fixes

* missing loadPlugin [#283](https://github.com/DavidWells/analytics/issues/283) ([40035c8](https://github.com/DavidWells/analytics/commit/40035c813886eb0bcafd9ba636da18987810f19d))





## [1.1.3](https://github.com/DavidWells/analytics/compare/@analytics/segment@1.1.2...@analytics/segment@1.1.3) (2022-01-02)

**Note:** Version bump only for package @analytics/segment





## [1.1.2](https://github.com/DavidWells/analytics/compare/@analytics/segment@1.1.1...@analytics/segment@1.1.2) (2021-10-29)

**Note:** Version bump only for package @analytics/segment





## [1.1.1](https://github.com/DavidWells/analytics/compare/@analytics/segment@1.1.0...@analytics/segment@1.1.1) (2021-09-14)

**Note:** Version bump only for package @analytics/segment





# [1.1.0](https://github.com/DavidWells/analytics/compare/@analytics/segment@0.6.1...@analytics/segment@1.1.0) (2021-04-19)


### Bug Fixes

* set name on page call with title by default or props.name ([69da370](https://github.com/DavidWells/analytics/commit/69da370))


### Features

* add support for multiple users using same client to pinpoint ([a6e6fba](https://github.com/DavidWells/analytics/commit/a6e6fba))





## [0.6.1](https://github.com/DavidWells/analytics/compare/@analytics/segment@0.6.0...@analytics/segment@0.6.1) (2021-01-29)

**Note:** Version bump only for package @analytics/segment





# [0.6.0](https://github.com/DavidWells/analytics/compare/@analytics/segment@0.5.2...@analytics/segment@0.6.0) (2021-01-04)


### Features

* add integrations config option to segment ([03d1e41](https://github.com/DavidWells/analytics/commit/03d1e41))





## [0.5.2](https://github.com/DavidWells/analytics/compare/@analytics/segment@0.5.1...@analytics/segment@0.5.2) (2020-12-13)

**Note:** Version bump only for package @analytics/segment





## [0.5.1](https://github.com/DavidWells/analytics/compare/@analytics/segment@0.5.0...@analytics/segment@0.5.1) (2020-11-11)


### Bug Fixes

* pass options to segment track call. Close [#108](https://github.com/DavidWells/analytics/issues/108) ([5430775](https://github.com/DavidWells/analytics/commit/5430775))





# [0.5.0](https://github.com/DavidWells/analytics/compare/@analytics/segment@0.4.3...@analytics/segment@0.5.0) (2020-09-25)


### Bug Fixes

* [#85](https://github.com/DavidWells/analytics/issues/85) ([8b1bc3d](https://github.com/DavidWells/analytics/commit/8b1bc3d))


### Features

* add .group to segment plugin ([f01da4b](https://github.com/DavidWells/analytics/commit/f01da4b))





## [0.4.3](https://github.com/DavidWells/analytics/compare/@analytics/segment@0.4.2...@analytics/segment@0.4.3) (2020-09-25)

**Note:** Version bump only for package @analytics/segment





## [0.4.2](https://github.com/DavidWells/analytics/compare/@analytics/segment@0.4.1...@analytics/segment@0.4.2) (2020-09-16)


### Bug Fixes

* segment plugin src match ([1ee2326](https://github.com/DavidWells/analytics/commit/1ee2326)), closes [#88](https://github.com/DavidWells/analytics/issues/88)





## [0.4.1](https://github.com/DavidWells/analytics/compare/@analytics/segment@0.4.0...@analytics/segment@0.4.1) (2020-08-15)

**Note:** Version bump only for package @analytics/segment





# [0.4.0](https://github.com/DavidWells/analytics/compare/@analytics/segment@0.3.0...@analytics/segment@0.4.0) (2019-10-31)


### Features

* **segment:** clear all localstorage on analytics.reset() ([ff9886e](https://github.com/DavidWells/analytics/commit/ff9886e))





# 0.3.0 (2019-10-14)


### Bug Fixes

* **segment-plugin:** fix race condition for analytics.js reading id from localstorage for .page calls ([08e9b7a](https://github.com/DavidWells/analytics/commit/08e9b7a))


### Features

* **customerio:** Add node version for customerio plugin ([81bd120](https://github.com/DavidWells/analytics/commit/81bd120))
* **plugin-segment:** add segment plugin ([41c7705](https://github.com/DavidWells/analytics/commit/41c7705))
* **segment:** add anonymous id sync ([13fd69e](https://github.com/DavidWells/analytics/commit/13fd69e))
* **segment:** add serverside implementation ([57b1674](https://github.com/DavidWells/analytics/commit/57b1674))
* **segment:** add syncAnonymousId setting ([4655845](https://github.com/DavidWells/analytics/commit/4655845))
* **segment:** update disableAnonTracking via bootstrap listener ([7eef8c9](https://github.com/DavidWells/analytics/commit/7eef8c9))
* **segment-plugin:** Add disableAnonymousTraffic options ([85322b7](https://github.com/DavidWells/analytics/commit/85322b7))





## [0.2.3](https://github.com/DavidWells/analytics/compare/analytics-plugin-segment@0.2.2...analytics-plugin-segment@0.2.3) (2019-10-07)

**Note:** Version bump only for package analytics-plugin-segment





## [0.2.2](https://github.com/DavidWells/analytics/compare/analytics-plugin-segment@0.2.1...analytics-plugin-segment@0.2.2) (2019-08-26)

**Note:** Version bump only for package analytics-plugin-segment





## [0.2.1](https://github.com/DavidWells/analytics/compare/analytics-plugin-segment@0.2.0...analytics-plugin-segment@0.2.1) (2019-08-14)

**Note:** Version bump only for package analytics-plugin-segment





# [0.2.0](https://github.com/DavidWells/analytics/compare/analytics-plugin-segment@0.1.7...analytics-plugin-segment@0.2.0) (2019-08-01)


### Features

* **segment:** add anonymous id sync ([13fd69e](https://github.com/DavidWells/analytics/commit/13fd69e))
* **segment:** add syncAnonymousId setting ([4655845](https://github.com/DavidWells/analytics/commit/4655845))





## [0.1.7](https://github.com/DavidWells/analytics/compare/analytics-plugin-segment@0.1.7...analytics-plugin-segment@0.1.7) (2019-07-13)


### Bug Fixes

* **segment-plugin:** fix race condition for analytics.js reading id from localstorage for .page calls ([08e9b7a](https://github.com/DavidWells/analytics/commit/08e9b7a))


### Features

* **customerio:** Add node version for customerio plugin ([81bd120](https://github.com/DavidWells/analytics/commit/81bd120))
* **plugin-segment:** add segment plugin ([41c7705](https://github.com/DavidWells/analytics/commit/41c7705))
* **segment:** add serverside implementation ([57b1674](https://github.com/DavidWells/analytics/commit/57b1674))
* **segment:** update disableAnonTracking via bootstrap listener ([7eef8c9](https://github.com/DavidWells/analytics/commit/7eef8c9))
* **segment-plugin:** Add disableAnonymousTraffic options ([85322b7](https://github.com/DavidWells/analytics/commit/85322b7))
