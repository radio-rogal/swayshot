# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) 
and this project adheres to [Semantic Versioning](http://semver.org/).

## Unreleased


## [2.2.0] - 2019-05-29
### Added
- User can define timestamp format.

## [2.1.0] - 2019-03-22
### Added
- Use `wl-clipboard` to copy screenshot path to clipboard.

## [2.0.1] - 2019-03-20
### Changed
- Fix issue of region screenshot, use anoter bindkeys: Shift + Print Scr

## [2.0.0] - 2019-03-20
### Added
- Use slurp for regions.
### Changed
- As [swaygrab was deprecated in sway 1.0](https://github.com/swaywm/sway/releases/tag/1.0) now it use grim.
- Rename to swayshot, was swaygrab-helper.

## 1.1.0 - 2017-07-22
### Added
- Now it can copy full path to clipboard with xsel or xclip

## 1.0.1 - 2017-07-20
### Fixed
- Remove the file extensions `.sh` in the config


## 1.0.0 - 2017-07-20
### Initial release
- Keyboard shortcuts for whole screen and focused window.

[2.2.0]: https://gitlab.com/racy/swayshot/compare/2.1.0...2.2.0
[2.1.0]: https://gitlab.com/racy/swayshot/compare/2.0.1...2.1.0
[2.0.1]: https://gitlab.com/racy/swayshot/compare/2.0.0...2.0.1
[2.0.0]: https://gitlab.com/racy/swayshot/compare/1.1.0...2.0.0