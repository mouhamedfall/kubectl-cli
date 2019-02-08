Role Name
=========

This role install kubectl command on a linux distribution.
It configures also bash completion.

Requirements
------------

For the moment, only ubuntu > 16.04 is supported

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Minimal playbook:

    - name: install kubectl
      hosts: localhost
      roles:
        - kubectl-cli

Using the example playbook
--------------------------

    cd ..
    ansible-playbook -K -i localhost kubectl-cli/playbook-example.yml

License
-------

BSD

Author Information
------------------

Mouhamed Fall
