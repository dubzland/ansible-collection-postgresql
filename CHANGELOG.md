# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0]

### Changed

- Update minimum ansible version to 2.16 (#17)

### Removed

- No longer managing the pb_hba file (see `ansible.community.postgresql`) (#16)

## [1.1.0] - 2024-05-11

### Added

- PostgreSQL client installation role (#13)

## [1.0.0] - 2024-05-08

### Added

- Configuration configuration and data root directories (#10)

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

[unreleased]: https://git.dubzland.com/dubzland/ansible-collections/postgresql/-/compare/v1.2.0...HEAD
[1.2.0]: https://git.dubzland.com/dubzland/ansible-collections/postgresql/-/compare/v1.1.0...v1.2.0
[1.1.0]: https://git.dubzland.com/dubzland/ansible-collections/postgresql/-/compare/v1.0.0...v1.1.0
[1.0.0]: https://git.dubzland.com/dubzland/ansible-collections/postgresql/-/compare/v0.0.2...v1.0.0
[0.0.2]: https://git.dubzland.com/dubzland/ansible-collections/postgresql/-/compare/v0.0.1...v0.0.2
[0.0.1]: https://git.dubzland.com/dubzland/ansible-collections/postgresql/-/tree/v0.0.1
