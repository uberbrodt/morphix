# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [v0.2.0]
### Added
- added atomorphify!
- added atomorphiform!

### Changed
- fixed error with empty lists in atomorphif* methods
- updated documentation
- improved testing

## [v0.1.0]
### Added
- added `partiphify/2` function for partitioning lists

### Changed
- several functions now return `%BadMapError{}` instead of function undefined errors.

## [v0.0.8]
### Added
- added partiphify! function for partitioning lists

## [v0.0.7]
### Added
- added compactify and compactiform functions for eliminating nil values from maps.

## [v0.0.4]
### Added
- added `:safe` option for `atomorphif*` functions, if used, only existing atoms will be used in string conversion.

### Changed
- `atomorphif*` functions do not use `String.to_existing_atom` unless `:safe` option is passed.

## [v0.0.3]
### Added
- `morphify!` and `morphify` functions
- `morphiflat!`
- use `String.to_existing_binary` in `atomorphif*` functions, with fallback to `String.to_binary`
- Credo for linting
- A lot of documentation
- This file

### Changed
- use `String.to_existing_atom` in `atomorphif*` functions, with fallback to `String.to_atom`
