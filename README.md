el-samba-share
=========

Create a Samba share

Requirements
------------


Role Variables
--------------

* sharename
* storagepath
* accessgroup

´´´bash

---
sharename: "share"
storagepath: "/mnt/datadisk"
accessgroup: "sg-share-access-full"

´´´´

Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      roles:
         - jesperberth.el_samba_share

License
-------

BSD

Author Information
------------------

Jesper Berth
