# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.3.4]

### Added:
- Public: Updated README with troubleshooting information and okhttp3 resolution guide.
- Public: Updated error responses to be more descriptive.

### Fixed:
- Public: Apply okhttp3 fix to SampleApp.
- Public: Add fix for XCode 12.5 to SampleApp Podfile.
- Public: Fix an iOS bug where the Onfido flow isn't presented to user if the rootViewController is not at the top of the view hierarchy.
- Public: Fix for bug with Android proguard rules

## [1.3.3] - 2021-02-26

### Added:
- Public: Added support for hide logo and cobranding enterprise features

## [1.3.2] - 2020-09-29

### Fixed:
- UI: Fixed iOS crash problem on Xcode12 simulator

## [1.3.1] - 2020-09-02

### Fixed:
- UI: Fixed iOS custom appearance problem on real device

## [1.3.0] - 2020-08-04

### Changed:
- Public: Upgraded android SDK version to 7.2.0

## [1.2.2] - 2020-07-16

### Fixed:
- Public: Added fix in Github Repository filter

## [1.2.0] - 2020-07-07

### Added:
- Public: Added custom localisation support for ios

### Changed:
- Public: Upgraded iOS SDK version

## [1.0.1] - 2020-04-16

### Fixed:
- Public: Added fix for bug where npm install in SampleApp is deleting files in SampleApp directory.

## [1.0.0] - 2020-04-15

### Added:
- Public: MVP release of React Native SDK.
