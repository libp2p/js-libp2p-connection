## 1.0.0 (2022-06-09)


### Trivial Changes

* initial commit [skip ci] ([1bf76de](https://github.com/libp2p/js-libp2p-connection/commit/1bf76dee4e364f9c64c5753a276ced391a8a4233))
* update readme and project config ([#1](https://github.com/libp2p/js-libp2p-connection/issues/1)) ([abad08b](https://github.com/libp2p/js-libp2p-connection/commit/abad08ba5224270c45dad32991041dee46a910ce))

## [@libp2p/connection-v2.0.3](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/connection-v2.0.2...@libp2p/connection-v2.0.3) (2022-05-24)


### Bug Fixes

* accept abort options in connection.newStream ([#219](https://github.com/libp2p/js-libp2p-interfaces/issues/219)) ([8bfcbc9](https://github.com/libp2p/js-libp2p-interfaces/commit/8bfcbc9ee883336f213cdfc83e477549ca368df5))

## [@libp2p/connection-v2.0.2](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/connection-v2.0.1...@libp2p/connection-v2.0.2) (2022-05-23)


### Bug Fixes

* make stream return types synchronous ([#217](https://github.com/libp2p/js-libp2p-interfaces/issues/217)) ([2fe61b7](https://github.com/libp2p/js-libp2p-interfaces/commit/2fe61b7fbeda2e549edf095a927d623aa8eb476b))

## [@libp2p/connection-v2.0.1](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/connection-v2.0.0...@libp2p/connection-v2.0.1) (2022-05-20)


### Bug Fixes

* update sibling deps ([#216](https://github.com/libp2p/js-libp2p-interfaces/issues/216)) ([0ceca65](https://github.com/libp2p/js-libp2p-interfaces/commit/0ceca658901e92de554c828105b328b88a1416f8))

## [@libp2p/connection-v2.0.0](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/connection-v1.1.5...@libp2p/connection-v2.0.0) (2022-05-20)


### ⚠ BREAKING CHANGES

* This adds closeWrite and closeRead checks in the tests, which will cause test failures for muxers that don't implement those

### Bug Fixes

* close streams when connection is closed ([#214](https://github.com/libp2p/js-libp2p-interfaces/issues/214)) ([88fcd58](https://github.com/libp2p/js-libp2p-interfaces/commit/88fcd586276e03dd740c7095f05e21754ac1f3b5)), closes [#90](https://github.com/libp2p/js-libp2p-interfaces/issues/90)
* update interfaces ([#215](https://github.com/libp2p/js-libp2p-interfaces/issues/215)) ([72e6890](https://github.com/libp2p/js-libp2p-interfaces/commit/72e6890826dadbd6e7cbba5536bde350ca4286e6))

## [@libp2p/connection-v1.1.5](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/connection-v1.1.4...@libp2p/connection-v1.1.5) (2022-04-08)


### Bug Fixes

* swap protobufjs for protons ([#191](https://github.com/libp2p/js-libp2p-interfaces/issues/191)) ([d72b30c](https://github.com/libp2p/js-libp2p-interfaces/commit/d72b30cfca4b9145e0b31db28e8fa3329a180e83))


### Trivial Changes

* update aegir ([#192](https://github.com/libp2p/js-libp2p-interfaces/issues/192)) ([41c1494](https://github.com/libp2p/js-libp2p-interfaces/commit/41c14941e8b67d6601a90b4d48a2776573d55e60))

## [@libp2p/connection-v1.1.4](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/connection-v1.1.3...@libp2p/connection-v1.1.4) (2022-03-15)


### Bug Fixes

* simplify transport interface, update interfaces for use with libp2p ([#180](https://github.com/libp2p/js-libp2p-interfaces/issues/180)) ([ec81622](https://github.com/libp2p/js-libp2p-interfaces/commit/ec81622e5b7c6d256e0f8aed6d3695642473293b))

## [@libp2p/connection-v1.1.3](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/connection-v1.1.2...@libp2p/connection-v1.1.3) (2022-02-27)


### Bug Fixes

* rename crypto to connection-encrypter ([#179](https://github.com/libp2p/js-libp2p-interfaces/issues/179)) ([d197f55](https://github.com/libp2p/js-libp2p-interfaces/commit/d197f554d7cdadb3b05ed2d6c69fda2c4362b1eb))

## [@libp2p/connection-v1.1.2](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/connection-v1.1.1...@libp2p/connection-v1.1.2) (2022-02-27)


### Bug Fixes

* update package config and add connection gater interface ([#178](https://github.com/libp2p/js-libp2p-interfaces/issues/178)) ([c6079a6](https://github.com/libp2p/js-libp2p-interfaces/commit/c6079a6367f004788062df3e30ad2e26330d947b))

## [@libp2p/connection-v1.1.1](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/connection-v1.1.0...@libp2p/connection-v1.1.1) (2022-02-10)


### Bug Fixes

* remove node event emitters ([#161](https://github.com/libp2p/js-libp2p-interfaces/issues/161)) ([221fb6a](https://github.com/libp2p/js-libp2p-interfaces/commit/221fb6a024430dc56288d73d8b8ce1aa88427701))

## [@libp2p/connection-v1.1.0](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/connection-v1.0.4...@libp2p/connection-v1.1.0) (2022-02-09)


### Features

* add peer store/records, and streams are just streams ([#160](https://github.com/libp2p/js-libp2p-interfaces/issues/160)) ([8860a0c](https://github.com/libp2p/js-libp2p-interfaces/commit/8860a0cd46b359a5648402d83870f7ff957222fe))

## [@libp2p/connection-v1.0.4](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/connection-v1.0.3...@libp2p/connection-v1.0.4) (2022-01-15)


### Trivial Changes

* update project config ([#149](https://github.com/libp2p/js-libp2p-interfaces/issues/149)) ([6eb8556](https://github.com/libp2p/js-libp2p-interfaces/commit/6eb85562c0da167d222808da10a7914daf12970b))

## [@libp2p/connection-v1.0.3](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/connection-v1.0.2...@libp2p/connection-v1.0.3) (2022-01-14)


### Bug Fixes

* update it-* deps to ts versions ([#148](https://github.com/libp2p/js-libp2p-interfaces/issues/148)) ([7a6fdd7](https://github.com/libp2p/js-libp2p-interfaces/commit/7a6fdd7622ce2870b89dbb849ab421d0dd714b43))

## [@libp2p/connection-v1.0.2](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/connection-v1.0.1...@libp2p/connection-v1.0.2) (2022-01-08)


### Trivial Changes

* add semantic release config ([#141](https://github.com/libp2p/js-libp2p-interfaces/issues/141)) ([5f0de59](https://github.com/libp2p/js-libp2p-interfaces/commit/5f0de59136b6343d2411abb2d6a4dd2cd0b7efe4))
* update package versions ([#140](https://github.com/libp2p/js-libp2p-interfaces/issues/140)) ([cd844f6](https://github.com/libp2p/js-libp2p-interfaces/commit/cd844f6e39f4ee50d006e86eac8dadf696900eb5))

# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 0.2.0 (2022-01-04)


### Bug Fixes

* update dialer tests ([#116](https://github.com/libp2p/js-libp2p-interfaces/issues/116)) ([c679729](https://github.com/libp2p/js-libp2p-interfaces/commit/c679729113feb963ff27815fcafd7af51f722df7))


### chore

* update libp2p-crypto and peer-id ([c711e8b](https://github.com/libp2p/js-libp2p-interfaces/commit/c711e8bd4d606f6974b13fad2eeb723f93cebb87))


### Features

* add auto-publish ([7aede5d](https://github.com/libp2p/js-libp2p-interfaces/commit/7aede5df39ea6b5f243348ec9a212b3e33c16a81))
* simpler peer id ([#117](https://github.com/libp2p/js-libp2p-interfaces/issues/117)) ([fa2c4f5](https://github.com/libp2p/js-libp2p-interfaces/commit/fa2c4f5be74a5cfc11489771881e57b4e53bf174))
* split out code, convert to typescript ([#111](https://github.com/libp2p/js-libp2p-interfaces/issues/111)) ([e174bba](https://github.com/libp2p/js-libp2p-interfaces/commit/e174bba889388269b806643c79a6b53c8d6a0f8c)), closes [#110](https://github.com/libp2p/js-libp2p-interfaces/issues/110) [#101](https://github.com/libp2p/js-libp2p-interfaces/issues/101)
* update package names ([#133](https://github.com/libp2p/js-libp2p-interfaces/issues/133)) ([337adc9](https://github.com/libp2p/js-libp2p-interfaces/commit/337adc9a9bc0278bdae8cbce9c57d07a83c8b5c2))


### BREAKING CHANGES

* requires node 15+
* not all fields from concrete classes have been added to the interfaces, some adjustment may be necessary as this gets rolled out





## [0.3.1](https://github.com/libp2p/js-libp2p-interfaces/compare/libp2p-connection@0.3.0...libp2p-connection@0.3.1) (2022-01-02)

**Note:** Version bump only for package libp2p-connection





# [0.3.0](https://github.com/libp2p/js-libp2p-interfaces/compare/libp2p-connection@0.2.0...libp2p-connection@0.3.0) (2022-01-02)


### Bug Fixes

* update dialer tests ([#116](https://github.com/libp2p/js-libp2p-interfaces/issues/116)) ([c679729](https://github.com/libp2p/js-libp2p-interfaces/commit/c679729113feb963ff27815fcafd7af51f722df7))


### Features

* simpler peer id ([#117](https://github.com/libp2p/js-libp2p-interfaces/issues/117)) ([fa2c4f5](https://github.com/libp2p/js-libp2p-interfaces/commit/fa2c4f5be74a5cfc11489771881e57b4e53bf174))





# [0.2.0](https://github.com/libp2p/js-libp2p-interfaces/compare/libp2p-connection@0.1.0...libp2p-connection@0.2.0) (2021-12-02)


### chore

* update libp2p-crypto and peer-id ([c711e8b](https://github.com/libp2p/js-libp2p-interfaces/commit/c711e8bd4d606f6974b13fad2eeb723f93cebb87))


### BREAKING CHANGES

* requires node 15+





# 0.1.0 (2021-11-22)


### Features

* split out code, convert to typescript ([#111](https://github.com/libp2p/js-libp2p-interfaces/issues/111)) ([e174bba](https://github.com/libp2p/js-libp2p-interfaces/commit/e174bba889388269b806643c79a6b53c8d6a0f8c)), closes [#110](https://github.com/libp2p/js-libp2p-interfaces/issues/110) [#101](https://github.com/libp2p/js-libp2p-interfaces/issues/101)


### BREAKING CHANGES

* not all fields from concrete classes have been added to the interfaces, some adjustment may be necessary as this gets rolled out
