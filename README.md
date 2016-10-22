## ansible-crashplan - [![Build Status](https://travis-ci.org/grimmjow8/ansible-crashplan.png)](https://travis-ci.org/grimmjow8/ansible-crashplan)

Ansible role installs the CrashPlan Backup Software.

Requirements
------------

- Tested on ansible 2.1.2.0

Variables
---------

__crashplan_dl_path - download path (default: ~/Downloads)
__crashplan_version - crashplan version (default: 4.7.0)

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: grimmjow8.ansible-crashplan }

Testing
-------

\<path\>/ansible-crashplan $ ansible-playbook test.yml 

License
-------

Licensed under the MIT License. See the LICENSE file for details.

Author Information
------------------

TBD
