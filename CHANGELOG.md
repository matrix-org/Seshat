# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 2.4.0 - 2023-04-14

- [[#117]] Add a feature to build with static sqlcipher and openssl

[#117]: https://github.com/matrix-org/seshat/pull/117

## 2.3.3 - 2022-01-24

- [[#106]] Bracket search terms so multiple words in a search term don't cause a syntax error
- [[#107]] Add precommit hooks

[#106]: https://github.com/matrix-org/seshat/pull/106
[#107]: https://github.com/matrix-org/seshat/pull/107

## 2.3.2 - 2022-01-14

- [[#09d03ae]] Fix the seshat-node build by removing the path dependency

[#09d03ae]: https://github.com/matrix-org/seshat/commit/09d03ae52700e5fd11d137841a02b5e9133d059c

## 2.3.1 - 2022-01-13

- [[#104]] Fix quote search when passing a room_id
- [[#103]] Upgrade our deps

[#104]: https://github.com/matrix-org/seshat/pull/104
[#103]: https://github.com/matrix-org/seshat/pull/103

## 2.3.0 - 2021-07-21

- [[#99]] Switch to a fork of neon-serde
- [[#95]] Update neon and switch to n-api

[#99]: https://github.com/matrix-org/seshat/pull/99
[#95]: https://github.com/matrix-org/seshat/pull/95

## 2.2.4 - 2021-03-26

- [[#82]] Replace the invalid usage of the used attribute

[#82]: https://github.com/matrix-org/seshat/pull/82

## 2.2.3 - 2021-01-15

- [[#78]] Revert to Tantivy 0.12.0 for now

[#78]: https://github.com/matrix-org/seshat/pull/78

## 2.2.2 - 2021-01-12

- [[#77]] Bump our deps and pin serde due to a module becoming private.

[#77]: https://github.com/matrix-org/seshat/pull/77

## 2.2.1 - 2020-10-05

- [[#74]] Improve the load times for the event context.
- [[#75]] Make the IV initialization in the encrypted directory more robust against overflows.

[#74]: https://github.com/matrix-org/seshat/pull/74
[#75]: https://github.com/matrix-org/seshat/pull/75

## 2.1.0 - 2020-06-24

### Added

- [[#69]] Add support to get the user version from the recovery database and add
      a shutdown method to the recovery database.

[#69]: https://github.com/matrix-org/seshat/pull/69

## 2.0.0 - 2020-06-19

### Added

- [[#67]] Added support to store user specific versions in the database.
- [[#65]] Added a method to check if a particular room is already indexed.
- [[#64]] Exposed a method to change the passphrase in the js bindings.
- [[#63]] Added support to paginate search results.
- [[#60]] Added serde serialize/deserialize implementations for most of our
      structs.

### Changed

- [[#66]] Changed the return type of the search methods, they now return a
      struct instead of a tuple. **This is a breaking change**.
- [[#62]] Made all encryption specific dependencies optional.
- [[#59]] Switched from failure to thiserror for our error types.

[#67]: https://github.com/matrix-org/seshat/pull/67
[#66]: https://github.com/matrix-org/seshat/pull/66
[#65]: https://github.com/matrix-org/seshat/pull/65
[#64]: https://github.com/matrix-org/seshat/pull/64
[#63]: https://github.com/matrix-org/seshat/pull/63
[#62]: https://github.com/matrix-org/seshat/pull/62
[#60]: https://github.com/matrix-org/seshat/pull/60
[#59]: https://github.com/matrix-org/seshat/pull/59
