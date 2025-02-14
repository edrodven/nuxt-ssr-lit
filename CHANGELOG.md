# Changelog

## [1.2.2](https://github.com/prashantpalikhe/nuxt-ssr-lit/compare/v1.2.1...v1.2.2) (2023-01-26)


### Bug Fixes

* handle v-if that results in no vnode and hydrate Lit after Vue ([#49](https://github.com/prashantpalikhe/nuxt-ssr-lit/issues/49)) ([e0f832e](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/e0f832e164880d2871bb1b7d529a8cfc037c4841))

## [1.2.1](https://github.com/prashantpalikhe/nuxt-ssr-lit/compare/v1.2.0...v1.2.1) (2023-01-20)


### Bug Fixes

* elementProperties is a Map and not a POJO ([#47](https://github.com/prashantpalikhe/nuxt-ssr-lit/issues/47)) ([87a03ef](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/87a03ef06813d629c57c54e2897f2ac5dd159f99))

## [1.2.0](https://github.com/prashantpalikhe/nuxt-ssr-lit/compare/v1.1.1...v1.2.0) (2023-01-19)


### Features

* process vue files outside the src dir ([#45](https://github.com/prashantpalikhe/nuxt-ssr-lit/issues/45)) ([84a9e33](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/84a9e33146731413fbba47ce3e06b6629bd4165a))

## [1.1.1](https://github.com/prashantpalikhe/nuxt-ssr-lit/compare/v1.1.0...v1.1.1) (2023-01-11)


### Bug Fixes

* error detecting boolean properties causing renderer to fail. ([#43](https://github.com/prashantpalikhe/nuxt-ssr-lit/issues/43)) ([a72c28f](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/a72c28f7dc20fe762018748f7d928f7bf009cdd3))

## [1.1.0](https://github.com/prashantpalikhe/nuxt-ssr-lit/compare/v1.0.5...v1.1.0) (2023-01-11)


### Features

* upgrade to lit-labs/ssr 3.0.0 and Nuxt 3 ([#40](https://github.com/prashantpalikhe/nuxt-ssr-lit/issues/40)) ([b3da81b](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/b3da81b4fdbb2468f7bbc4b1f03b3a1d27f20a93))

## [1.0.5](https://github.com/prashantpalikhe/nuxt-ssr-lit/compare/v1.0.4...v1.0.5) (2022-11-22)


### Bug Fixes

* **#36:** always load the dom shim if the nuxt-ssr-lit module is used ([#37](https://github.com/prashantpalikhe/nuxt-ssr-lit/issues/37)) ([c95ca36](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/c95ca36d9a6412a036e42f81c1fee784a0324af1))

## [1.0.4](https://github.com/prashantpalikhe/nuxt-ssr-lit/compare/v1.0.3...v1.0.4) (2022-11-17)


### Bug Fixes

* properties of elements can be incorrectly rendered. Fixes [#30](https://github.com/prashantpalikhe/nuxt-ssr-lit/issues/30) ([#31](https://github.com/prashantpalikhe/nuxt-ssr-lit/issues/31)) ([ea32b7f](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/ea32b7ff01444817bfaeeb65f865537968f4dcb4))

## [1.0.3](https://github.com/prashantpalikhe/nuxt-ssr-lit/compare/v1.0.2...v1.0.3) (2022-11-15)


### Bug Fixes

* changed config key to ssrLit. Fixes [#27](https://github.com/prashantpalikhe/nuxt-ssr-lit/issues/27) ([#28](https://github.com/prashantpalikhe/nuxt-ssr-lit/issues/28)) ([184fb57](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/184fb573c8e5a38d8e5262d8d686093a8c80b785))

## [1.0.2](https://github.com/prashantpalikhe/nuxt-ssr-lit/compare/v1.0.1...v1.0.2) (2022-11-14)


### Bug Fixes

* upgrade release process to node 16 ([#25](https://github.com/prashantpalikhe/nuxt-ssr-lit/issues/25)) ([01a5c2a](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/01a5c2acafe7390ffa3e87669dc118ff0d5dcb7b))

## [1.0.1](https://github.com/prashantpalikhe/nuxt-ssr-lit/compare/v1.0.0...v1.0.1) (2022-11-14)


### Bug Fixes

* add build step to release-please ([416419e](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/416419e4a71ab5029542b4885610207105dc9c58))
* release-please doesn't auto-release ([206bf28](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/206bf28a585c632851143e21a5666e84a437c899))

## 1.0.0 (2022-11-14)

### Features

* add support for default slot ([ea7a08c](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/ea7a08cea3c3025d7a1d602f295daf1630a8881e))
* auto wrap lit elements ([333b682](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/333b6825d43fa99691aee7f051bb690cfa8a9492))
* log out ssr error ([b80c19e](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/b80c19e48b38e2eb217336971276934f7a229748))
* setup module ([9c1de9b](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/9c1de9bc096096470f1aca4e8745db8c86768810))
* take control of client and sever components ([#16](https://github.com/prashantpalikhe/nuxt-ssr-lit/issues/16)) ([d19475d](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/d19475d6537bd70b5f916ac3acd0636a0fe9ae77))
* update playground test cases ([84d19fd](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/84d19fdaabb7e6c5cbe7a2c2c93aeb89eb47e5e2))
* update playground to include many test scenarios ([48c8981](https://github.com/prashantpalikhe/nuxt-ssr-lit/commit/48c898192f6056ff75ed577e5363090bea63c1cc))
