# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).


## [Unreleased]

### Added
- CODE_OF_CONDUCT.md, CONTRIBUTING.md

### Changed
- `.evaluate()` now returns the resulting value or a Promise [#110](https://github.com/graphcool/chromeless/pull/110) @joelgriffith
- README improvements. @timsuchanek @adieuadieu @hax @Chrisgozd @githubixx @d2s @vladgolubev

### Fixed
- Ensure latest version of Serverless is used during deployment. [#58](https://github.com/graphcool/chromeless/issues/58)
- package repository url [#64](https://github.com/graphcool/chromeless/pull/64) @Hazealign


## [1.0.1] - 2017-07-27
### Added
- CHANGELOG.md
- LICENSE file (MIT)
- `implicitWait`: By default wait for `.press` and `.click` for a cleaner workflow

### Changed
- `.end()`: now returns the last value

### Fixed
- The cookie commands broke the queue, now they work like expected

### Changed
- Many README improvements. @schickling @sorenbs @emeth- @timsuchanek @adieuadieu @toddwprice


## [1.0.0] - 2017-07-26
### Added
- Initial public release
- Initial version of Chromeless
- Initial version of Chromeless Proxy
