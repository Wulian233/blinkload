# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## `v1.2.1` - 31/12/2024

### Fixed

- A crash that occurred when trying to load from the atlas texture cache (on the 2nd startup)

## `v1.2.0` - 28/12/2024

### Added

- Localization support for the mod description (by [Wulian233](https://github.com/Wulian233) in [#15](https://github.com/steves-underwater-paradise/blinkload/pull/15))
  - `zh_cn` mod description translation

### Fixed

- Various crashes that could occur due to an invalid cache file or `IOException`s when reading from disk (by [Wulian233](https://github.com/Wulian233) in [#15](https://github.com/steves-underwater-paradise/blinkload/pull/15))

## `v1.1.0` - 08/09/2024

### Changed

- The hash to use the list of enabled resource packs on top of the mod list

### Fixed

- Mipmap levels not being saved to the cache, causing broken mipmaps when loading atlas textures from the cache
- An occasional native crash when saving atlas textures to the cache

## `v1.0.0` - 29/08/2024

Initial release.
