# Changelog

## [0.3.9 ] - 2021-03-17
 - Updated dependencies

### Fixed
 - Black camera texture issue on iOS 14.x
## Breaking Changes
 - `<a-entity camera zappar-camera>` will no longer request camera permissions. You must now use ` <a-entity zappar-compatibility-ui>` for camera permissions.
## [0.3.8 ] - 2021-02-11
 - Updated dependencies

## [0.3.7] - 2021-02-11

## Changed
 - Updated dependencies
 - Updated README to reference support for iOS WKWebView from iOS 14.3 and later

### Added
 - Table of contents to `README.md`
 - `.SkipVersionLog` to disable console logging current version
 - ESLint
 - Issue templates - `bug_report.md` & `feature_request.md`
 - Dependabot
 - Build status badges to `README.md`

### Fixed
 - All internal methods now have valid return types

## [0.3.6] - 2021-02-08

### Added
 - Table of contents to `README.md`

### Fixed
 - Issue where `zappar-permissions-ui` does not show the UI


## [0.3.5] - 2020-11-26

### Added
 - This changelog :-)
 - Console log the version when the library is initialized

### Fixed
 - Ensure internal GL usage correctly sets the expected active texture
 - Prevent flickering when there are no new camera frames
 - Fixed building with recent versions of `worker-loader`

### Changed
 - Dependencies update
 - Remove unnecessary console logging


## [0.2.6] - 2020-11-18

### Added
 - Permissions UI customization
 - Browser compatibility API and UI
 - README section detailing browser support
 - Support for face landmarks
 - Greatly improved face tracking model
 - Functions to THREE objects to dispose of underling Zappar JS objects
 - Support for ThreeJS versions >= 0.118.*
 - Fixed issue where face meshes disappear when close to the edge of the screen

### Fixed
 - Fixes to iPad support
 - Support for Firefox
 - Camera now correctly destroys the two CameraSource objects it owns


## [0.2.5] - 2020-09-16

### Changed
 - README syntax highlighting improvements


## [0.2.4] - 2020-09-15

### Fixed
 - Fix issues with iOS 14
 - Use browser `visiblitychange` event to pause/start camera when user changes tabs
 - Tweaks to computer vision algorithms

### Changed
 - Dependencies update


## [0.2.3] - 2020-06-12

### Added
 - Support for full head meshes


## [0.2.2] - 2020-06-02

Initial release
