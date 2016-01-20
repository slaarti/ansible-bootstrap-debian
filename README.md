# Bootstrap Debian

Installs the minimum requirements for using Ansible on Debian/Ubuntu hosts.

The role installs the `python`, `python-apt`, `python-pycurl` and `aptitude`
packages (if not already available).

The typical use case for this role is scripted creation of new hosts or
automatic preparation of existing hosts for Ansible management.

Requirements
------------

The host machine should run Debian or Ubuntu.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - slaarti.bootstrap-debian

License
-------

Unlicense; see the LICENSE file.

Author Information
------------------

Chris Pinard <slaarti@gmail.com>
