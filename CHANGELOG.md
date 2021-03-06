# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## 0.4.1 - 2016-01-06
- Fix Apache FOP performance degradation with DITA-OT 2.4.x

## 0.4.0 - 2016-07-04
- Fix support for Gradle 2.14
- Add support for automatically installing DITA-OT plugins #8

## 0.3.1 — 2016-04-29
- Fix support for Gradle 2.13
- Improve input file detection logic
- Fix support for scenarios where DITA-OT libraries aren't yet available in the
  project evaluation phase.

## 0.3.0 — 2016-03-11
- Add support for multiple transtypes
- Fix classpath conflicts and update classpath compilation strategy

## 0.2.1 – 2016-01-22
- Fix Java 7 compatibility

## 0.2.0 — 2015-12-04
- Add useAssociatedFilter property
- Ignore `.gradle` directory in up-to-date check
- Run Ant in headless mode (see [dita-ot/dita-ot#2140](https://github.com/dita-ot/dita-ot/issues/2140)).

## 0.1.0 — 2015-10-31
- Initial release
