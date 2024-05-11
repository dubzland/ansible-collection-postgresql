# Ansible Collection: PostgreSQL

[![Gitlab pipeline][pipeline-badge]][pipeline-url]
[![Gitlab coverage][coverage-badge]][coverage-url]
[![Galaxy Version][galaxy-badge]][galaxy-url]
[![license][license-badge]][license-url]
[![Liberapay patrons][liberapay-patrons-badge]][liberapay-url]
[![Liberapay receiving][liberapay-receives-badge]][liberapay-url]

Collection of roles for interacting with the
[PostgreSQL](https://www.postgresql.org/) database server on Debian/Ubuntu
servers.

## Ansible version compatibility

This collection has been tested against following ansible-core versions:

- 2.14
- 2.15
- 2.16

Also tested against the current development version of `ansible-core`.

## Included content

### Roles

| Name                                                       | Description                                      |
| ---------------------------------------------------------- | ------------------------------------------------ |
| [dubzland.postgresql.postgresql_common][postgresql_common] | Common tasks required for both client and server |
| [dubzland.postgresql.postgresql_client][postgresql_client] | Installs the PostgreSQL client tools             |
| [dubzland.postgresql.postgresql_server][postgresql_server] | Installs and configures the PostgreSQL server    |

## Licensing

This collection is primarily licensed and distributed as a whole under the MIT license.

See [LICENSES/MIT.txt](LICENSES/MIT.txt) for the full text.

## Author

- [Josh Williams](https://dubzland.com)

[pipeline-badge]: https://img.shields.io/gitlab/pipeline-status/dubzland%2Fansible-collections%2Fpostgresql?gitlab_url=https%3A%2F%2Fgit.dubzland.com&branch=main&style=flat-square&logo=gitlab
[pipeline-url]: https://git.dubzland.com/dubzland/ansible-collections/postgresql/pipelines?scope=all&page=1&ref=main
[coverage-badge]: https://img.shields.io/gitlab/pipeline-coverage/dubzland%2Fansible-collections%2Fpostgresql?gitlab_url=https%3A%2F%2Fgit.dubzland.com&branch=main&style=flat-square&logo=gitlab
[coverage-url]: https://git.dubzland.com/dubzland/ansible-collections/postgresql/pipelines?scope=all&page=1&ref=main
[galaxy-badge]: https://img.shields.io/badge/dynamic/json?style=flat-square&label=galaxy&prefix=v&url=https://galaxy.ansible.com/api/v3/collections/dubzland/postgresql/&query=highest_version.version
[galaxy-url]: https://galaxy.ansible.com/ui/repo/published/dubzland/postgresql/
[license-badge]: https://img.shields.io/gitlab/license/dubzland%2Fcontainer-images%2Fci-python?gitlab_url=https%3A%2F%2Fgit.dubzland.com&style=flat-square
[license-url]: https://git.dubzland.com/dubzland/container-images/ci-python/-/blob/main/LICENSE
[liberapay-patrons-badge]: https://img.shields.io/liberapay/patrons/jdubz?style=flat-square&logo=liberapay
[liberapay-receives-badge]: https://img.shields.io/liberapay/receives/jdubz?style=flat-square&logo=liberapay
[liberapay-url]: https://liberapay.com/jdubz/donate
[postgresql_common]: https://docs.dubzland.io/ansible-collections/collections/dubzland/postgresql/postgresql_common_role.html
[postgresql_client]: https://docs.dubzland.io/ansible-collections/collections/dubzland/postgresql/postgresql_client_role.html
[postgresql_server]: https://docs.dubzland.io/ansible-collections/collections/dubzland/postgresql/postgresql_server_role.html
