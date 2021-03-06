# Changelog
This changelog is for Nikkolai's Input Debugger package for Unity. All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), 
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.3.2] - 2020-06-14
### Fixed
- Update `registry` under `publishConfig` to include scope.

## [1.3.1] - 2020-06-14
### Fixed
- Fixed links in CHANGELOG.md.
- Update package.json to include missing `publishConfig` section.

## [1.3.0] - 2020-06-14
### Changed
- Convert from Unity project to Unity Package Manager (UPM) file layout.

## [1.2.1] - 2018-04-20
### Fixed
- Fixed component help button by adding a HelpURL attribute with a link to the wiki.

## [1.2.0] - 2018-04-18
### Changed
- Added support for logging when buttons are released.
- Added support for logging input buttons listed in the Input Manager.
- Added UnityEvents for handling changes in axis values and button states. 
- Reduced iterations per update by omitting invalid inputs.

## [1.1.0] - 2018-04-18
### Changed
- Added `axisNames` field to expose axis names to the inspector.
- Disable InputDebugger in non-development builds.

## [1.0.0] - 2018-04-18
### Added
- InputDebugger script and demo scene.


[Unreleased]: https://github.com/wcoastsands/input-debugger/compare/v1.3.2...HEAD
[1.3.2]: https://github.com/wcoastsands/input-debugger/compare/v1.3.1...v1.3.2
[1.3.1]: https://github.com/wcoastsands/input-debugger/compare/v1.3.0...v1.3.1
[1.3.0]: https://github.com/wcoastsands/input-debugger/compare/v1.2.1...v1.3.0
[1.2.1]: https://github.com/wcoastsands/input-debugger/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/wcoastsands/input-debugger/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/wcoastsands/input-debugger/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/wcoastsands/input-debugger/releases/tag/v1.0.0
