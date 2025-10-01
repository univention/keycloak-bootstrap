# Changelog

## [0.17.6](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.17.5...v0.17.6) (2025-10-01)


### Bug Fixes

* remove pined version of univention-keycloak-client ([d526bb2](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/d526bb20538012e4e070545d52f777dee6ff1af9)), closes [univention/dev/internal/team-nubus#1424](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1424)

## [0.17.5](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.17.4...v0.17.5) (2025-09-18)


### Bug Fixes

* Make the Keycloak client name static and not dynamic ([d5a18cd](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/d5a18cd4e67549622e0a76a03bb4fe59d994290b)), closes [univention/dev/internal/team-nubus#1435](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1435)
* pin the new version ([1b212b0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/1b212b0c373b57e41134ae58b479788ca30dd59e)), closes [univention/dev/internal/team-nubus#1435](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1435)

## [0.17.4](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.17.3...v0.17.4) (2025-09-17)


### Bug Fixes

* add --use-refresh-tokens to UMC OAuth 2.0 client ([a05b6f4](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/a05b6f483e3bc486884b002bd384327037f8df5f)), closes [univention/dev/internal/team-nubus#1435](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1435)

## [0.17.3](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.17.2...v0.17.3) (2025-09-16)


### Bug Fixes

* **deps:** Update dependency univention/dev/nubus-for-k8s/common-ci to v1.44.7 ([bafb645](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/bafb6453ea0295a40ad37f582909bdf280539898)), closes [#0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/issues/0)

## [0.17.2](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.17.1...v0.17.2) (2025-09-16)


### Bug Fixes

* **deps:** Update dependency univention/dev/nubus-for-k8s/common-ci to v1.44.6 ([a7f297c](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/a7f297cc8456d92d7d83b8b534b4f5e4fbbb3830)), closes [#0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/issues/0)

## [0.17.1](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.17.0...v0.17.1) (2025-09-15)


### Bug Fixes

* avoid using --force ([8ad41e6](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/8ad41e6d2f781533b9317546b4053abaaea16bfa)), closes [univention/dev/internal/dev-issues/dev-incidents#158](https://git.knut.univention.de/univention/dev/internal/dev-issues/dev-incidents/issues/158)
* ping right version ([b9ab205](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/b9ab205bc3f9ae915c0b6b1fcf8359f9b3440a7e)), closes [univention/dev/internal/dev-issues/dev-incidents#158](https://git.knut.univention.de/univention/dev/internal/dev-issues/dev-incidents/issues/158)

## [0.17.0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.16.5...v0.17.0) (2025-09-12)


### Features

* **keycloak-bootstrap:** add OIDC Relying Party client for UMC ([efaed2f](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/efaed2f938d8eba4ebf5ed1450106dbd58a2e04c)), closes [univention/dev/internal/dev-issues/dev-incidents#138](https://git.knut.univention.de/univention/dev/internal/dev-issues/dev-incidents/issues/138)


### Bug Fixes

* **docker:** Bump version of keycloak client, old version is gone ([277d133](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/277d133082e220f584e0c7dade11cf84839abc34)), closes [univention/dev/internal/dev-issues/dev-incidents#138](https://git.knut.univention.de/univention/dev/internal/dev-issues/dev-incidents/issues/138)
* **helm:** Rename some valaues/variable to make their meaning clearer ([f1f2159](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/f1f2159687faddd385bffb1bebc7cb385bd074f5)), closes [univention/dev/internal/dev-issues/dev-incidents#138](https://git.knut.univention.de/univention/dev/internal/dev-issues/dev-incidents/issues/138)
* **keycloak-bootstrap:** Cleanup and use nubus-common as base ([93a9303](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/93a9303038ef07e0103f319920739dabb8201f82)), closes [univention/dev/internal/dev-issues/dev-incidents#138](https://git.knut.univention.de/univention/dev/internal/dev-issues/dev-incidents/issues/138)
* **keycloak-bootstrap:** Handle secrets correctly ([9db79f9](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/9db79f93579acf2dd007c98bac3fb9ab91492b40)), closes [univention/dev/internal/dev-issues/dev-incidents#138](https://git.knut.univention.de/univention/dev/internal/dev-issues/dev-incidents/issues/138)

## [0.16.5](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.16.4...v0.16.5) (2025-09-12)


### Bug Fixes

* Upgrade base image to 5.2-3 and added new custom package ([214c848](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/214c84857ab7efdf40e1320c95f36784af996bc4)), closes [#0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/issues/0)

## [0.16.4](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.16.3...v0.16.4) (2025-09-06)


### Bug Fixes

* **deps:** Update dependency univention/dev/nubus-for-k8s/common-ci to v1.44.4 ([f781073](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/f7810736e6c7eb6b57120ad0b09c975b008465d0)), closes [#0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/issues/0)

## [0.16.3](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.16.2...v0.16.3) (2025-09-01)


### Bug Fixes

* Correct dockerfile to be in line with our base image approach ([5b4ac4c](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/5b4ac4cade968d9c25a837d487e609dd4e93752e)), closes [univention/dev/internal/team-nubus#1385](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1385)
* Use a customized version of univention-keycloak ([0bf5a75](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/0bf5a7571a549af0ea979ea50e6ed0d87fb5570b)), closes [univention/dev/internal/team-nubus#1385](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1385)

## [0.16.2](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.16.1...v0.16.2) (2025-08-28)


### Bug Fixes

* **deps:** Update dependency univention/dev/nubus-for-k8s/common-ci to v1.44.2 ([7b4782a](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/7b4782a0523a3f7418e485449cee7ab89aaa909e)), closes [#0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/issues/0)

## [0.16.1](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.16.0...v0.16.1) (2025-08-27)


### Bug Fixes

* **deps:** Update gitregistry.knut.univention.de/univention/dev/projects/ucs-base-image/ucs-base Docker tag to v5.2.2-build.20250821 ([5bff82b](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/5bff82bb036874e044d837bef15acce746c238a7)), closes [#0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/issues/0)

## [0.16.0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.15.5...v0.16.0) (2025-08-26)


### Features

* upgrade bitnami charts ([7312fc8](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/7312fc8399a4f0c63fdef2bc59c826fd6be43e09)), closes [univention/dev/internal/team-nubus#1406](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1406)

## [0.15.5](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.15.4...v0.15.5) (2025-08-19)


### Bug Fixes

* **deps:** Update gitregistry.knut.univention.de/univention/dev/projects/ucs-base-image/ucs-base Docker tag to v5.2.2-build.20250814 ([cb01ae8](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/cb01ae83618508f9a70a6a86547cc65a217bdcda)), closes [#0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/issues/0)

## [0.15.4](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.15.3...v0.15.4) (2025-08-19)


### Bug Fixes

* **deps:** Update dependency univention/dev/nubus-for-k8s/common-ci to v1.44.1 ([7612c44](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/7612c446f53bca1d0fd61923e38e657c5024005a)), closes [#0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/issues/0)

## [0.15.3](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.15.2...v0.15.3) (2025-08-18)


### Bug Fixes

* **helm:** Blank lines after | are not valid yaml. Make the helm output parseable by ruamel ([2f35d20](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/2f35d20d0db56e7df6976a529aa968879000d5f9)), closes [univention/dev/internal/team-nubus#989](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/989)

## [0.15.2](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.15.1...v0.15.2) (2025-08-01)


### Bug Fixes

* trigger release, use wait-for-keycloak script ([130a7da](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/130a7dab091f28c76b53d8c73d18ded05799108f)), closes [#0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/issues/0)

## [0.15.1](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.15.0...v0.15.1) (2025-07-29)


### Bug Fixes

* **univention-keycloak:** added `univention-keycloak` from an ucs branch. ([1def197](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/1def197f5033d9f250790050167551d2bd2be988)), closes [univention/dev/internal/team-nubus#1355](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1355)
* **univention-keycloak:** remove local `univention-keycloak` copy. ([806f487](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/806f487004ae29f846d3e14c4c3ad05a5230669a)), closes [univention/dev/internal/team-nubus#1355](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1355)

## [0.15.0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.14.0...v0.15.0) (2025-07-17)


### Features

* update wait-for-dependency to 0.35.0 ([528debc](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/528debc7e93a19870ea7b12b12a439a81201aef7)), closes [univention/dev/internal/team-nubus#1320](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1320)

## [0.14.0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.13.0...v0.14.0) (2025-07-17)


### Features

* update ucs-base to 5.2.2-build.20250714 ([37cb4a8](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/37cb4a8964c3fe6477bd6a64e9ee8f4844b06395)), closes [univention/dev/internal/team-nubus#1320](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1320)

## [0.13.0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.12.2...v0.13.0) (2025-07-01)


### Features

* enable frontchannel logout for the UMC SAML client ([9529fbf](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/9529fbf0b0db744f75dc0c80dcd94ecf20a74cde)), closes [univention/dev/internal/team-nubus#1238](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1238)

## [0.12.2](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.12.1...v0.12.2) (2025-06-21)


### Bug Fixes

* use the right wait-for-dependency image ([570f7a2](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/570f7a27762d47d7f792e9b8d85df7d3a7ceed52)), closes [univention/dev/internal/team-nubus#1263](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1263)

## [0.12.1](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.12.0...v0.12.1) (2025-06-18)


### Bug Fixes

* bump umc-base-image version ([85747ad](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/85747ad3e2915d85cfa49037f3a370d8bd639a8a)), closes [univention/dev/internal/team-nubus#1263](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1263)

## [0.12.0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.11.0...v0.12.0) (2025-05-11)


### Features

* move and upgrade ucs-base-image to 0.17.3-build-2025-05-11 ([4850498](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/48504986e48efe5c498f4669148b286178bc9b9d))


### Bug Fixes

* add bitnami to package-helm-charts ([d9980f1](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/d9980f1c19f7e27952ab2382eacbb5c8def4348e))
* move addlicense pre-commit hook ([d2bd9c9](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/d2bd9c951b4a54b41da2659ef3d387b7f3e07f68))
* update common-ci to main ([4109991](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/41099916ebce2bbbd9444216fc0e0be9629d2a6d))

## [0.11.0](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/compare/v0.10.2...v0.11.0) (2025-04-29)


### Features

* Bump ucs-base-image to 5.2-1 ([2965442](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/2965442fc20fc98269c43b1ee5b08ff2fb1044c9)), closes [univention/dev/internal/team-nubus#1155](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1155)


### Bug Fixes

* final version of wait-for-dependency ([66142db](https://git.knut.univention.de/univention/dev/projects/keycloak/keycloak-bootstrap/commit/66142dbe6542365c5a2c072d3a398da9a134755d)), closes [univention/dev/internal/team-nubus#1155](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1155)

## [0.10.2](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.10.1...v0.10.2) (2025-03-21)


### Bug Fixes

* fix namespace template in serviceacount ([48c971c](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/48c971c111998ae8b478b8bf92e82760fa733238)), closes [univention/dev/internal/team-nubus#1075](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1075)

## [0.10.1](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.10.0...v0.10.1) (2025-02-26)


### Bug Fixes

* Bump wait-for-dependency image ([6a92dcd](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/6a92dcda15fbe74c2a6f7b03db01c92d3a7c9532))

## [0.10.0](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.9.1...v0.10.0) (2025-02-26)


### Features

* Bump ucs-base-image to use released apt sources ([fbe6e41](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/fbe6e41c98330f9c31097f4f7d7b30f48709e846))

## [0.9.1](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.9.0...v0.9.1) (2025-02-10)


### Bug Fixes

* add .kyverno to helmignore ([2f6361e](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/2f6361e51f313b5975a77bfb62a08449c8a61e11))

## [0.9.0](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.8.0...v0.9.0) (2025-01-16)


### Features

* rely on initContainers instead of helm hooks ([b392ee6](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/b392ee6a55a9e2cdd1208fcb3be2cecc8c90e88f))


### Bug Fixes

* QA changes ([117924c](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/117924c6b7bf5ece20c2f2fbb55118eb348fe37a))
* workaround to avoid bugged univention-keycloak version ([b086179](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/b0861799020f6ef37acfaab718d94a28594b016e))

## [0.8.0](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.7.1...v0.8.0) (2024-12-20)


### Features

* upgrade UCS base image to 2024-12-12 ([7d2e988](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/7d2e9880231ca441628e990d733c10851ecbf004))

## [0.7.1](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.7.0...v0.7.1) (2024-11-27)


### Bug Fixes

* kyverno lint ([9286892](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/9286892eeab2070e08c1eedba86e6976f987737a))
* lint ([f2db8ff](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/f2db8fffb923f48d54be1be35fdaa12b5778e53d))
* set ro filesystem ([f3809ff](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/f3809ffc3126b98a73157ee8bdfe314a7b027010))
* upgrade univention-keycloak-client version ([c9aee64](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/c9aee64d37d98ec4f31b80516e8236eef5a7ff16))

## [0.7.0](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.6.0...v0.7.0) (2024-11-13)


### Features

* migrate components secrets ([2b0f08a](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/2b0f08a85a3b085ebf5f230fdf45c800b6744cb0))


### Bug Fixes

* QA changes ([b55c4e3](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/b55c4e37a3deaa53b531151e70684b37e58a4895))

## [0.6.0](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.5.0...v0.6.0) (2024-10-22)


### Features

* added portal to the keycloak realm CSP ([3babdab](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/3babdabd4858523d3c86e3a891fca1c404be9a99))

## [0.5.0](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.4.0...v0.5.0) (2024-10-15)


### Features

* enable realm user events on initialization ([81d33b3](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/81d33b3ebeb45adea230eb512e20e2faf88e21c6))

## [0.4.0](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.3.0...v0.4.0) (2024-09-26)


### Features

* **ci:** enable malware scanning, disable sbom generation ([be86335](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/be86335b65189bae64cf6306d1bf8eee81968c7b))

## [0.3.0](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.2.1...v0.3.0) (2024-09-13)


### Features

* update UCS base image to 2024-09-09 ([2ccfa54](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/2ccfa54598d8634f8b4613e3419cc159c18f6556))


### Bug Fixes

* upgrade ansible package ([d3c15fa](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/d3c15fa9276dbbf06e93a4281bc03ef838f4c546))

## [0.2.1](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.2.0...v0.2.1) (2024-09-11)


### Bug Fixes

* disable logging of credentials ([f1de6b7](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/f1de6b7b518486684dd213982f85339f4ef47168))

## [0.2.0](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.1.2...v0.2.0) (2024-08-27)


### Features

* upgrade univention-keycloak for Keycloak 25 ([b9cf98b](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/b9cf98b7d9a82e2d949be5ead2a21220089ab69e))

## [0.1.2](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.1.1...v0.1.2) (2024-08-16)


### Bug Fixes

* bump univention-keycloak version ([0f6f5e2](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/0f6f5e2249ced58d7a66f195e8b57d2c3aac8fcd))

## [0.1.1](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.1.0...v0.1.1) (2024-07-25)


### Bug Fixes

* unfork leftovers ([f09a143](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/f09a1430a130725f88cd5aa7bab3e14c00d4085e))

## [0.1.0](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.0.2...v0.1.0) (2024-05-14)


### Features

* changes to support the refactored umbrella values in a nubus deployment ([a215ed5](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/a215ed5620875597d6bccee1b1992c3021f52917))


### Bug Fixes

* add assertions to ansible code to catch errors early ([97ece42](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/97ece425ba1886074dbabb9e3b93f8b15a2d0b8f))
* adjust ansible variable naming, fix assertions ([6207b83](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/6207b83817aa71ede0c92309e792efc9d007d214))

## [0.0.2](https://git.knut.univention.de/univention/components/keycloak-bootstrap/compare/v0.0.1...v0.0.2) (2024-05-08)


### Bug Fixes

* update common-ci ([43bf6f8](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/43bf6f8cedb091093073815b7dae5f9644879d71))

## 0.0.1 (2024-05-08)


### Features

* initial commit (migration from souvap repos) ([69ba8a9](https://git.knut.univention.de/univention/components/keycloak-bootstrap/commit/69ba8a985885bee0d94e8df295b86686e2f9515e))
