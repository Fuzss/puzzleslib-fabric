# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog].

## [v3.3.0-1.18.2] - 2022-03-03
- Updated to Minecraft 1.18.2
### Changed
- Made config system more aware of what parts have been loaded yet to avoid accidentally accessing data too early

## [v3.2.1-1.18.1] - 2022-02-25
### Added
- Added tooltip utility methods for checking if certain modifier keys are pressed

## [v3.2.0-1.18.1] - 2022-02-22
### Added
- Added system for managing Cardinal Components API as a Fabric alternative to Forge's capabilities

## [v3.1.5-1.18.1] - 2022-02-10
### Fixed
- Made it more clear when category comments in a config are not supported

## [v3.1.4-1.18.1] - 2022-02-09
### Fixed
- Fixed an issue with some category comments being unable to apply

## [v3.1.3-1.18.1] - 2021-12-28
### Fixed
- Fixed an ordering issue when loading configs 

## [v3.1.2-1.18.1] - 2021-12-24
### Added
- Added helper class for accessing hidden fields on screen instances
### Changed
- Enabled mixins

## [v3.1.1-1.18.1] - 2021-12-15
### Added
- Added more helper methods for registering sound events and items

## [v3.1.0-1.18.1] - 2021-12-12
- Compiled for Minecraft 1.18.1

## [v3.0.2-1.18] - 2021-12-11
### Added
- Added a helper method for converting a list of registry entries to string

## [v3.0.1-1.18] - 2021-12-05
### Added
- Added utility classes for working with json files
### Fixed
- Fixed an issue where configs wouldn't load very often on start-up

## [v3.0.0-1.18] - 2021-12-02
- Ported to Minecraft 1.18

[Keep a Changelog]: https://keepachangelog.com/en/1.0.0/