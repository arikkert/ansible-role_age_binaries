Role Name
=========

- have *age* binaries installed for RedHat family
- have *age* package installed for Debian family, hmm you won't need an ansible role for that ;-)

Galaxy : yes

Requirements
------------

RedHat/Debian

Role Variables
--------------

- *location_src*: temporary directory, defaults to /var/tmp
- *location_dst*: install directory, defaults to /usr/local/bin/

Dependencies
------------

go binairies, I think no dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - arikkert.age_binaries

License
-------

BSD

Author Information
------------------

    ARK-ICT
    Andre Rikkert de Koe - ICT
