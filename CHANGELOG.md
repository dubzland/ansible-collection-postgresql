# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- Allow molecule tests to use the matrix provided by Gitlab CI (#6)
- Update molecule image to `ci-systemd` 1.1 (#5)
- Update CI process to use `ci-templates` (#1)
- Updated minimum supported ansible version to 2.14 (#4)

### Fixed

- PostgreSQL version actually gets used during install (#9)

## [0.0.2] - 2023-12-05

### Fixed

- Documentation links in the README.

## [0.0.1] - 2023-12-01

### Added

- Ansible role `postgresql_common` for configuring apt repositories
- Ansible role `postgresql_server` for installing and configuring the server

[unreleased]: https://git.dubzland.com/dubzland/ansible-collections/postgresql/-/compare/0.0.2...HEAD
[0.0.2]: https://git.dubzland.com/dubzland/ansible-collections/postgresql/-/compare/0.0.1...0.0.2
[0.0.1]: https://git.dubzland.com/dubzland/ansible-collections/postgresql/-/tree/0.0.1
