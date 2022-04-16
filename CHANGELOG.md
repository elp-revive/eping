# Changelog

All notable changes to this project are documented in this file.

## Changelog Format

This changelog format is based on [Keep a Changelog][changelog].

[changelog]: <https://web.archive.org/web/20201014163139/https://keepachangelog.com/en/1.0.0/>

## Semantic Versioning

This project adheres to the [SemVar][semvar] version of semantic
versioning.

[semvar]: <https://web.archive.org/web/20201009135328/https://semver.org/>

## Date Format

This project uses the [ISO 8601 date format][iso] of (YYYY-MM-DD).

[iso]: <https://web.archive.org/web/20201012024406/https://www.iso.org/iso-8601-date-and-time-format.html>

## [Unreleased]

### Fixed
- Support windows ping.exe (a45a33122b49f26a47fbe1afa924cc9db4b85e74)
- Add CI (3e4f64aee09bcbce741cac020b5fb0409fb89ed0)

## [0.1.1] - 2020-10-19

### Fixed
- Use lexical bindings to improve performance.

## [0.1.0] - 2020-10-18

### Add
- Readme
- Changelog
- BSD zero clause license (SPDX: 0BSD)
- `eping` interactive function to check internet connectivity from
  within Emacs using `ping`.
- Configurable `eping-domain-options` variable that the user can
  select from when prompted for a domain to ping.
- Configurable `eping-number-pings-options` variable that user can
  select from when prompted for the number of pings.
- Info documentation
- HTML documentation
