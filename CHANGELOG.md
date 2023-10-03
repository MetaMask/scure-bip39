# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.1.1]
### Added
- Add `node.engines` field indicating minimum Node.js version 16 to package manifest ([#21](https://github.com/MetaMask/scure-bip39/pull/21))

### Changed
- Bump `@noble/hashes` from `~1.1.1` to `~1.3.2` ([#20](https://github.com/MetaMask/scure-bip39/pull/20))
- Bump `@scure/base` from `~1.1.0` to `~1.1.3` ([#20](https://github.com/MetaMask/scure-bip39/pull/20))

## [2.1.0]
### Added
- Update `mnemonicToSeed` (async version) to accept mnemonic arg formatted as `Uint8Array` the same as the synchronous version already does ([#14](https://github.com/MetaMask/scure-bip39/pull/14))

## [2.0.4]
### Fixed
- Fixes file path to typescript types in `package.json` ([#12](https://github.com/MetaMask/scure-bip39/pull/12))

## [2.0.3]
### Changed
- Update entrypoint for package [#10](https://github.com/MetaMask/scure-bip39/pull/10)

## [2.0.2] [DEPRECATED]
### Changed
- change build output location to `/dist` [#9](https://github.com/MetaMask/scure-bip39/pull/9)

## [2.0.1] [DEPRECATED]
### Added
- add publishConfig [#6](https://github.com/MetaMask/scure-bip39/pull/6)

## [2.0.0] [DEPRECATED]
### Changed
- Apply patches to allow passing mnemonic as a Uint8Array instead of as a string [#1](https://github.com/MetaMask/scure-bip39/pull/1)

[Unreleased]: https://github.com/MetaMask/scure-bip39/compare/v2.1.1...HEAD
[2.1.1]: https://github.com/MetaMask/scure-bip39/compare/v2.1.0...v2.1.1
[2.1.0]: https://github.com/MetaMask/scure-bip39/compare/v2.0.4...v2.1.0
[2.0.4]: https://github.com/MetaMask/scure-bip39/compare/v2.0.3...v2.0.4
[2.0.3]: https://github.com/MetaMask/scure-bip39/compare/v2.0.2...v2.0.3
[2.0.2]: https://github.com/MetaMask/scure-bip39/compare/v2.0.1...v2.0.2
[2.0.1]: https://github.com/MetaMask/scure-bip39/compare/v2.0.0...v2.0.1
[2.0.0]: https://github.com/MetaMask/scure-bip39/releases/tag/v2.0.0
