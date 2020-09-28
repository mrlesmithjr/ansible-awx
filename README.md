# ansible-awx

Ansible role to install/configure Ansible AWX

> NOTE: AWX provides a web-based user interface, REST API, and task engine built
> on top of Ansible. It is the upstream project for Tower, a commercial derivative
> of AWX.

## Build Status

### GitHub Actions

![Molecule Test](https://github.com/mrlesmithjr/ansible-awx/workflows/Molecule%20Test/badge.svg)

### Travis CI

[![Build Status](https://travis-ci.org/mrlesmithjr/ansible-awx.svg?branch=master)](https://travis-ci.org/mrlesmithjr/ansible-awx)

## Requirements

For any required Ansible roles, review:
[requirements.yml](requirements.yml)

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

## Example Playbook

[playbook.yml](playbook.yml)

# Usage

Login to AWX dashboard by accessing `http://HostnameOrIP` and login with `user:pass`
defined in [defaults/main.yml](defaults/main.yml) under:

```yaml
user: awx['default_admin_user']
pass: awx['default_admin_password']
```

## License

MIT

## Author Information

Larry Smith Jr.

- [@mrlesmithjr](https://twitter.com/mrlesmithjr)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)
- [http://everythingshouldbevirtual.com](http://everythingshouldbevirtual.com)

> NOTE: Repo has been created/updated using [https://github.com/mrlesmithjr/cookiecutter-ansible-role](https://github.com/mrlesmithjr/cookiecutter-ansible-role) as a template.
