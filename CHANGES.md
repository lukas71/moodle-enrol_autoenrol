# Changelog
All notable changes to this project will be documented in this file.

## [Unreleased]
### Added
- user enrolment manual confirmation option by [Andrew Hancox](https://github.com/andrewhancox)

## [2.3.3] - 2021-06-30
### Added
- a CLI script to check and enable new enrolments in all instances
- an admin setting to enable availability plugin used by autoenrol

## [2.3.2] - 2021-06-17
### Fixed
- Data validation for welcome message sender #26
- Default value of customint4 (Allow new enrolments) in old instances

## [2.3.1] - 2021-06-10
### Added
- Data validation to editing form

### Changed
- First option in Group by dropdown menu from *Choose* to a more easy to understand *Do not create groups*

### Fixed
- Removed double quote in SQL that broke 2.3 upgrade on PostgreSQL

## [2.3] - 2021-05-17
### Added
- Enrolment duration.
- Unenrol inactive after.

### Changed
- Renewed user filtering, now with Moodle standard availability interface.
- No more available filtering by language and authenticantion method (additional availability plugins needed).

## [2.2] - 2021-03-08
### Added
- Command line script and scheduled task for batch auto enrolment.

### Fixed
- Just enrolled courses in Dashboard with auto enrol on login.

## [2.1.1] - 2019-11-18
### Added
- Backup and restore support.

## [2.1] - 2018-10-19
### Added
- Bulk operations.
- API Privacy support.
- Self unenrol.

## [2.0] - 2016-12-20
### Added
- Custom profile fields support.
- Method delete feature.
- Auto unenrol when profile field changes and it do not match the filter.
- Group remove/change when profile field change.

### Fixed
- Coding style to pass Moodle code checker tests.

## [1.3.1] - 2015-02-20
### Added
- New capability to control whether user can enable or disable instances.

### Changed
- Tweaks to the Readme to improve readability and installation instructions.

## [1.3] - 2014-11-30
### Added
- New setting option to control the group cleanup behaviour.

### Changed
- Release for Moodle 2.6, 2.7 and 2.8.
- Groups now identified by group idnumber instead of name (so feel free to rename groups!).

## [1.2] - 2013-07-01
### Added
- It is now possible to add multiple instances to a single course.
- An option to give instance a custom label.
- An option to limit number of enrolments. 
- A permission for users to unenrol themselves if not enrolling during login.

### Changed
- Filtering functions now allow for partial matches.
- Expanded filtering functions to include email address.
- By default, users are now only enrolled if they aren't already enrolled on a course.
- Individual users can now be manually unenrolled through Users > Enrolled Users.

## [1.1] - 2013-05-08
### Changed
- Improved instance configuration form compatibility with Moodle 2.5.

## [1.0] - 2013-01-23
### Added
- New config option to "Add instance to new courses".

## [0.9.1] - 2012-09-27
### Fixed
- Filtering was being bypassed when enrolling on site-login.

## [0.9] - 2012-06-13
### Added
- Initial commit
