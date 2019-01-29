=========================
ansible-role-borgmatic
=========================

Ansible role to manage borgmatic

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-borgmatic.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-borgmatic
* Bugs: https://bugs.launchpad.net/ansible-role-borgmatic

Description
-----------

A simple wrapper script for the Borg backup software that creates and prunes
backups.

Requirements
------------

* pip3 to be installed if using borgmatic_install_method: (git|pip)

See `bindep.txt` for role dependencies.

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install borgmatic
      hosts: foo
      roles:
        - ansible-role-borgmatic
