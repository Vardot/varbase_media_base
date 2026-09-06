# Changelog

All notable changes to the Varbase Media Base recipe are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0] - 2026-09-06
### Changed
- Release the Varbase Media Base recipe as stable 1.0.0 with the Varbase 11.0.0 suite.
- Pin the `drupal/varbase_media` dependency to `~11.0.0` for the release.
- Update the version badge to `1.0.0` in `README.md`.

## [1.0.0-rc2] - 2026-09-02
### Added
- Require the `vardot/dropzone` library (`^5.9.3`), so the Dropzone files
  `drupal/dropzonejs` loads are actually on disk. No upstream Dropzone 5 release ships the
  `dropzone-min.js` filename the module declares, so the library was previously absent.
### Changed
- Pin the `drupal/varbase_media` dependency to `~11.0.0` for the release.
- Update the version badge to `1.0.0-rc2` in `README.md`.

## [1.0.0-rc1] - 2026-08-15
### Changed
- Release the recipe with the Varbase 11.0.0-rc1 suite. No functional changes since 1.0.0-beta1.
- Pin the `drupal/varbase_media` to `~11.0.0` dependency for the release.
- Update the version badge to `1.0.0-rc1` in `README.md`.

## [1.0.0-beta1] - 2026-07-09
### Changed
- Update Drupal Core from ~11.3.0 to ~11.4.0 in the Varbase Media Base recipe.
- Pin the `drupal/varbase_media` dependency to `~11.0.0`.
- Update the version badge to `1.0.0-beta1` in `README.md`.
- Run CI on tag pushes and add the README pipeline and release badges.

## [1.0.0-alpha2] - 2026-06-21
### Changed
- Maintenance and dependency updates for the Varbase Media Base recipe.

## [1.0.0-alpha1]
### Added
- Initial release of the Varbase Media Base recipe.

[Unreleased]: https://git.drupalcode.org/project/varbase_media_base/-/compare/1.0.0...1.0.x
[1.0.0]: https://git.drupalcode.org/project/varbase_media_base/-/compare/1.0.0-rc2...1.0.0
[1.0.0-rc2]: https://git.drupalcode.org/project/varbase_media_base/-/compare/1.0.0-rc1...1.0.0-rc2
[1.0.0-rc1]: https://git.drupalcode.org/project/varbase_media_base/-/compare/1.0.0-beta1...1.0.0-rc1
[1.0.0-beta1]: https://git.drupalcode.org/project/varbase_media_base/-/compare/1.0.0-alpha2...1.0.0-beta1
[1.0.0-alpha2]: https://git.drupalcode.org/project/varbase_media_base/-/compare/1.0.0-alpha1...1.0.0-alpha2
[1.0.0-alpha1]: https://git.drupalcode.org/project/varbase_media_base/-/tags/1.0.0-alpha1
