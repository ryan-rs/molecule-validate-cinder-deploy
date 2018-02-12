Role Name
=========

This is a simple test repo using the [molecule framework](https://molecule.readthedocs.io/en/latest/)
for deploying system state via [ansible](https://www.ansible.com/)
and validating that state using
[infratest](https://testinfra.readthedocs.io/en/latest/).

Requirements
------------

The following packages should be installed via pip in order to run molecule.
```
pip install molecule testinfra python-vagrant ansible docker-py
```

This branch uses docker as its driver, so docker must be installed on the
system running molecule.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-ntp, x: 42 }

License
-------

Apache

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
