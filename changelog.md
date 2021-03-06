# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [2.4.95] - 2018-09-7
### Added
- Builds in AWS now include the MISP version number in the image description *[(Screenshot)](https://github.com/MISP/misp-cloud/blob/master/docs/images/ami-listing.png)*

### Changed
- MISP 2.4.95
- Bootstrap script updated for non-interactive dpkg
- us-west-2 - Additional region added (Fixes Issue [#4](https://github.com/MISP/misp-cloud/issues/4)) 

### Removed
- N/A

## [2.4.94] - 2018-09-29
### Added
- GnuPG is enabled by default

### Changed
- Base OS has changed to Ubuntu 18.04
- Better defaults for MISP configuration
- MISP 2.4.94
- Updated development files, "MISP and Cloud Security" and AWS installation guide

### Removed
- [Viper](https://github.com/viper-framework/viper) is not included
- [Mail2MISP](https://github.com/MISP/mail_to_misp) is not included
- [MISP-Dashboard](https://github.com/MISP/misp-dashboard/) is not included
