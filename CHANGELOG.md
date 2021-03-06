<!-- markdownlint-disable no-duplicate-header line-length -->

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.0] - 29 December 2018

### Add

- Tests for selector

### Change

- Resolve API call inside action. List methods no longer needs to explicitly return a Promise.

## [0.2.2] - 9 December 2018

### Change

- Fix `isLoaded` selector not checking corect date property

## [0.2.0] - 8 December 2018

### Add

- Add state selector to [`buildList`](src/index.js#L57) export
- Add test for [`create`](src/create/create.test.js), [`find`](src/find/find.test.js), [`update`](src/update/update.test.js) and [`delete`](src/delete/delete.test.js) actions

## [0.1.0] - 26 November 2018

First

[Unreleased]: https://github.com/asd14/redux-all-is-list/compare/v0.3.0...HEAD

[0.3.0]: https://github.com/asd14/redux-all-is-list/compare/v0.2.2...v0.3.0
[0.2.2]: https://github.com/asd14/redux-all-is-list/compare/v0.2.0...v0.2.2
[0.2.0]: https://github.com/asd14/redux-all-is-list/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/asd14/redux-all-is-list/compare/v0.1.0
