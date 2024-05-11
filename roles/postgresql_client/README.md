# Ansible Role: PostgreSQL Client

Installs the PostgreSQL database client tools.

## Usage

Install the collection locally, either via `requirements.yml`, or manually:
```bash
ansible-galaxy collection install dubzland.postgresql
```

Then apply the client role using the following playbook:
```yaml
---
- hosts: db-clients

  roles:
    - dubzland.postgresql.postgresql_client
```
## License

MIT

## Author

* [Josh Williams](https://codingprime.com)
