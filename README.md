ansible-role-ntp
======

This role is intended to install NTP, and manage ntp.conf.


Variables (optional)
------

```
ansible_role_ntp_cfg_path: /path/to/group_files/ntp/ntp.conf
```


Notes
------

If ansible_role_ntp_cfg_path is undefined, the existing file will be left untouched.

At the time of this writing, only Ubuntu is supported.
