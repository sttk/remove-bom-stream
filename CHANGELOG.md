# Changelog

## [2.0.0](https://www.github.com/sttk/remove-bom-stream/compare/v1.2.0...v2.0.0) (2022-04-19)


### ⚠ BREAKING CHANGES

* Require encoding option to avoid inspecting chunks for UTF-8 encoding (#8)
* Normalize repository, dropping node <10.13 support (#3)

### Features

* Remove the dependency on `remove-bom-buffer` ([2107f34](https://www.github.com/sttk/remove-bom-stream/commit/2107f343cf48a5032fd0a8c2af09cc882f77c12c))
* Require encoding option to avoid inspecting chunks for UTF-8 encoding ([#8](https://www.github.com/sttk/remove-bom-stream/issues/8)) ([2107f34](https://www.github.com/sttk/remove-bom-stream/commit/2107f343cf48a5032fd0a8c2af09cc882f77c12c))
* Use node core's `TextDecoder` to process beginning of stream ([2107f34](https://www.github.com/sttk/remove-bom-stream/commit/2107f343cf48a5032fd0a8c2af09cc882f77c12c))


### Bug Fixes

* Handle first chunk shorter than 7 bytes correctly when next chunks are larger ([#7](https://www.github.com/sttk/remove-bom-stream/issues/7)) ([564f87b](https://www.github.com/sttk/remove-bom-stream/commit/564f87b7760210f0aa348d82ea01fe5d98b4c20a))


### Miscellaneous Chores

* Normalize repository, dropping node <10.13 support ([#3](https://www.github.com/sttk/remove-bom-stream/issues/3)) ([8fece9c](https://www.github.com/sttk/remove-bom-stream/commit/8fece9c9cc1760a3593d4c04fa275b3fe8867c35))
