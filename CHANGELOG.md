# Changelog
All notable changes from v1.0.0 will be documented in this file.

## [1.14.2] - 2020-06-22
### Fixed
- Not applying width, height properties for Panorama container

## [1.14.1] - 2020-06-22
### Fixed
- Not working API key in config. Rename apiKey to apikey in IConfig interface
- Wrong return type of AngularYandexMapsModule.forRoot(...)

## [1.14.0] - 2020-06-05
### Changed
- IConfig interface, add new properties from API

## [1.13.1] - 2020-05-21
### Changed
- README, update usage section

## [1.13.0] - 2020-05-21
### Added
- Support map localization

### Changed
- Now forRoot() accepts IConfig instead of string

## [1.12.0] - 2020-04-24
### Added
- Support for changing ContentChild after map init (E.g. Issue#11)

## [1.11.4] - 2020-04-02
### Added
- Export types: ILoadEvent & IEvent

## [1.11.3] - 2020-03-31
### Fixed
- The conflict between Bootstrap's container and library

## [1.11.2] - 2020-03-25
### Changed
- README, replace examples list by link to docs

## [1.11.0] - 2020-01-22
### Added
- onlyInstance input. With that option, entities aren't creating. The map only returns ILoadEvent.

## [1.10.3] - 2020-01-10
### Changed
- README. Move documentation to [Angular-Yandex-Maps-Docs](https://ddubrava.github.io/angular-yandex-maps-docs/)

## [1.10.2] - 2020-01-02
### Changed
- forRoot() is optional for AngularYandexMapsModule

## [1.10.1] - 2019-11-27
### Fixed
- Lazy loading of YMaps script

## [1.10.0] - 2019-11-22
### Changed
- IEvent - ymaps: any is added

### Added
- ILoadEvent - { instance: any, ymaps: any }

## [1.9.0] - 2019-11-19
### Added
- Map outputs
- Panorama outputs
- Placemark outputs
- MultiRoute outputs
- GeoObject outputs

## [1.8.0] - 2019-11-19
### Changed
- Output 'onInit' renamed to 'load'

## [1.7.3] - 2019-11-17
### Added
- New examples in README

## [1.7.2] - 2019-11-17
### Changed
- Fix anchors in README

## [1.7.1] - 2019-11-17
### Changed
- Fix anchors in README

## [1.7.0] - 2019-11-17
### Added
- Control component, supports all Controls of Yandex.Map API

### Removed
- Search Control component

## [1.6.0] - 2019-11-16
### Added
- Panorama component

## [1.5.0] - 2019-11-15
### Added
- Clusterer for Placemark in Map inputs

### Changed
- Inputs of Map

## [1.4.0] - 2019-11-09
### Changed
- Inputs of Map
- Inputs of Placemark
- Inputs of MultiRoute

## [1.3.0] - 2019-10-30
### Added
- Angular 6+ support

## [1.2.1] - 2019-10-27
### Changed
- Update README

## [1.2.0] - 2019-10-27
### Added
- Search component

### Changed
- Error logging message and logic
- Cleanup app.html

## [1.1.0] - 2019-10-27
### Added
- GeoObject component
- Error logging for Map, Placemark, Multiroute components

### Removed
- YandexMapModule types

## [1.0.1] - 2019-10-26
### Changed
- Change README examples

## [1.0.0] - 2019-09-14
- Release without changes

[1.14.2]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.14.1...v1.14.2
[1.14.1]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.14.0...v1.14.1
[1.14.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.13.1...v1.14.0
[1.13.1]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.13.0...v1.13.1
[1.13.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.12.0...v1.13.0
[1.12.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.11.4...v1.12.0
[1.11.4]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.11.3...v1.11.4
[1.11.3]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.11.2...v1.11.3
[1.11.2]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.11.0...v1.11.2
[1.11.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.10.3...v1.11.0
[1.10.3]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.10.2...v1.10.3
[1.10.2]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.10.1...v1.10.2
[1.10.1]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.10.0...v1.10.1
[1.10.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.9.0...v1.10.0
[1.9.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.8.0...v1.9.0
[1.8.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.7.3...v1.8.0
[1.7.3]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.7.2...v1.7.3
[1.7.2]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.7.1...v1.7.2
[1.7.1]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.7.0...v1.7.1
[1.7.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.6.0...v1.7.0
[1.6.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.5.0...v1.6.0
[1.5.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.4.0...v1.5.0
[1.4.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.3.0...v1.4.0
[1.3.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.2.1...v1.3.0
[1.2.1]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.0.1...v1.1.0
[1.0.1]: https://github.com/ddubrava/angular-yandex-maps/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/ddubrava/angular-yandex-maps/compare/v0.1.1...v1.0.0
