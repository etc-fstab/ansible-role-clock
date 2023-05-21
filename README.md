Role Name
=========
This is Ansible role for managing clock. 
It's chrony for Linux and ntp for Solaris. 

The clock/time is managed based on (in this order):

- Host based conf
- Hosts group based conf
- Location

Role Variables
--------------

1. Common vars:

```time_mgmt``` (default 'yes')

2. The OS family vars:

```time_pkg```,  ```time_service```, ```time_cfg_file```, ```driftfile```

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
