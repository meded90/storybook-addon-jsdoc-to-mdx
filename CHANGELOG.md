# Changelog

All significant changes to the project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project respects [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2025-04-25

### Added
- Support for HTML tags in JSDoc comments through automatic escaping
- Enhanced documentation with complete examples and troubleshooting section
- Support for latest Storybook versions (8.6.x)

### Fixed
- Fixed MDX parsing errors when JSDoc comments contain HTML tags
- Added workaround for Storybook SWC compiler issues

## [1.0.4] - 2025-01-06

### Changed
- Updated package.json

## [1.0.3] - 2024-02-18

### Changed
- Updated package.json

## [1.0.2] - 2024-02-18

### Changed
- Updated README.md

## [1.0.1] - 2024-02-18

### Added
- Files added: CHANGELOG.md, .npmignore

### Changed
- Added "files" section in package.json

### Fixed
- Fixed an issue with the dist directory being missing in the NPM repository

## [1.0.0] - 2024-02-17

### Added
- First release of a plugin that allows generating MDX documentation from JSDoc comments.
