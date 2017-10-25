andrewrothstein.nss-pam-ldap-configure
======================================
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-nss-pam-ldap-configure.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-nss-pam-ldap-configure)

Configure NSS/PAM for LDAP.

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
    - andrewrothstein.nss-pam-ldap-configure
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
