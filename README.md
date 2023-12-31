# Ansible Collection: PostgreSQL

[![Gitlab pipeline status (self-hosted)](https://git.dubzland.com/dubzland/ansible-collection-postgresql/badges/main/pipeline.svg)](https://git.dubzland.com/dubzland/ansible-collection-postgresql/pipelines?scope=all&page=1&ref=main)
[![Ansible Galaxy](https://img.shields.io/badge/dynamic/json?style=flat&label=galaxy&prefix=v&url=https://galaxy.ansible.com/api/v3/collections/dubzland/postgresql/&query=highest_version.version)](https://galaxy.ansible.com/ui/repo/published/dubzland/minio/)
[![Liberapay patrons](https://img.shields.io/liberapay/patrons/jdubz)](https://liberapay.com/jdubz/donate)
[![Liberapay receiving](https://img.shields.io/liberapay/receives/jdubz)](https://liberapay.com/jdubz/donate)

Collection of roles for interacting with the
[PostgreSQL](https://www.postgresql.org/) database server on Debian/Ubuntu
servers.

## Ansible version compatibility

This collection has been tested against following ansible-core versions:

- 2.13
- 2.14
- 2.15
- 2.16

Also tested against the current development version of `ansible-core`.

## Included content

### Roles

| Name                                                       | Description                                      |
| ---------------------------------------------------------- | ------------------------------------------------ |
| [dubzland.postgresql.postgresql_common][postgresql_common] | Common tasks required for both client and server |
| [dubzland.postgresql.postgresql_server][postgresql_server] | Installs and configures the PostgreSQL server    |

## Licensing

This collection is primarily licensed and distributed as a whole under the GNU General Public License v3.0 or later.

See [LICENSE](https://git.dubzland.com/dubzland/ansible-collection-minio/blob/main/LICENSE) for the full text.

## Author

- [Josh Williams](https://dubzland.com)

[postgresql_common]: https://docs.dubzland.io/ansible-collections/collections/dubzland/postgresql/postgresql_common_role.html
[postgresql_server]: https://docs.dubzland.io/ansible-collections/collections/dubzland/postgresql/postgresql_server_role.html
