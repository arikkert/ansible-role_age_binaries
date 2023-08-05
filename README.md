Role Name
=========

have *age* binaries installed

Galaxy : yes

Requirements
------------

RedHat compatible 7 or higher, CentOS, Almalinux, Rockylinux.

Role Variables
--------------

*location_src*: temporary directory, defaults to /var/tmp
*location_dst*: install directory, defaults to /usr/local/bin/ 

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
