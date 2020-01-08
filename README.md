ansible-role-tunnel
=========

This role installs a full tunneling solution
- Privoxy
- ssh tunnel
- optional http_proxy

Requirements
------------

EPEL (RHEL)

Role Variables
--------------

```
socks_proxy: ""
http_proxy: ""
```

Dependencies
------------

`geerlingguy.git`

Example Playbook
----------------

```
- hosts: all
  roles:
    - { role: joscherrer.tunnel }
```

License
-------

MIT

Author Information
------------------

Jonathan Scherrer
