Role Name
=========
This is Ansible role for managing clock. The clock/time is managed based on:

- Host conf.

- Hosts group confg (if no host cfg).

- Ansible OS Family conf (if no host/group cfg).

Role Variables
--------------

1. Common vars:

```time_mgmt``` (default 'yes')

2. The OS family vars:

```time_pkg```,  ```time_service```, ```driftfile```

3. Host, hostgroup, location based vars:

```timezone```, ```time_conf```

Dependencies
------------
None.

Example Playbook
----------------
See tests folder. 

Author Information
------------------
ZD

License
--------

Public domain.
No ownership such as copyright, trademark, patent. No warranty. 
