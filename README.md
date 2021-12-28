andrewrothstein.pkg-upgrade
=========
![Build Status](https://github.com/andrewrothstein/ansible-pkg-upgrade/actions/workflows/build.yml/badge.svg)

Pulls in all package upgrades available with the package manager. This role is *not* idempotent.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.pkg-upgrade
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
