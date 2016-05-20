OULibraries.iscsi-initiator
=========

iSCSI initiator role for OUlib.

Requirements
------------

A target system running CentOS7x.

Role Variables
--------------
All of the info you would need in a typical mutual CHAP configuration, eg.
```
iscsi:
    portal: targetip
    target: targetiqn
    initiator: initiatoriqn
    username: initatorchapusername
    password: initiatorchappassword
    username_in: targetchapusername
    password_in: targetchappassword
    timeout: 600
```

Dependencies
------------


Example Playbook
----------------


License
-------

TBD

Author Information
------------------

Jason Sherman
