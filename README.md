[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-pkg-upgrade.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-pkg-upgrade)
andrewrothstein.pkg-upgrade
=========

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

    - hosts: servers
      roles:
         - andrewrothstein.pkg-upgrade

License
-------

MIT

Author Information
------------------

Andrew Rothstein andrew.rothstein@gmail.com
