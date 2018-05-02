A Playbook, that installs the basic tools of an SysAdmin.
=========

This playbook will install on Debian the Chrome Browser, Emma (Remote MySQL), FileZilla, Java, PidGin, Pulse Secure, Remmina(Remote Desktop), Sublime Text, xFceTerm(terminal).

Requirements
------------

- OS Debian (This playbook is developed for Debian native OS, but can work properly with Debian Based OS)

Role Variables
--------------

This Playbook will use just facts of Ansible, import_tasks, and will gotcha everything from a main playbook, everything will be referenced at tests/test.yml for a correct run, more details will be described below.

Dependencies
------------

You will not need have any another playbook or thing, this playbook is complete, and all content of config files for example, are attached at files/templates.

Example Playbook
----------------

This playbook need be executed from tests directory with command `ansible-playbook -i /etc/ansible/inventories/testing/ test.yml` for example, there is the test.yml content:

    - hosts: all
      roles:
         -  role: ../..

License
-------

GNU

Author Information
------------------

Hello, my name is Igor, an IT & Infosec Expert, regex pro player and devops skills to made everything happens fast.
