# Change Log
All notable changes to this project will be documented in this file.

## 0.3.7 - 2016-02-17
### Added
- Additional test coverage for files permissions.

### Changed
- Fixes to swagger definition impacting files permissions, postits, and profiles.
- Added limit and offset parameters to swagger definitions for endpoints returning collection listings.

### Removed
- No change.


## 0.3.6 - 2016-02-15
### Added
- No change

### Changed
- Fixed bug uploading binary files.

### Removed
- No change.


## 0.3.5 - 2016-02-09
### Added
- async.py, module with convenience class for handling.
- significant increase in tests.

### Changed
- Fixed issue where boolean parameters were being ignored.
- Fixed issues in the Notification model preventing basic use of that service.
- Fixed issues in the Profile model preventing basic use of that service.
- Fixed issues in the Metadata model preventing basic use of that service.
- Fixed issue with public/private parameter definition for systems.
- Fixed issue where error was returned if services (properly) returned an empty response.


### Removed
- No change.


## 0.3.4 - 2016-02-04
### Added
- No change

### Changed
- Fixed issue with token auto-refresh failing for tenants with v 1.9 of APIM.

### Removed
- No change.


## 0.3.3 - 2016-02-04
### Added
- Project CHANGELOG.md file.

### Changed
- Fixed issues publishing to PyPI, including URL and requirements.
- Fixed README to refer to github project home.

### Removed
- No change.
