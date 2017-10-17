SSH update role
=========

modify ssh ansible galaxy role.

Requirements
------------

None

Role Variables
--------------

* ssh_client_port  
ssh cllient default port

* ssh_server_port  
ssh server port

* ssh_gssapi_authentication_enabled  
enable GSSAPIAuthentication

Dependencies
------------

None

Example Playbook
----------------

```yml
---
- hosts: all
  become: true
  roles:
    - { role: ssh, ssh_client_port: 22, ssh_server_port: 22 }
```

License
-------

BSD

Author Information
------------------

[Daisuke Maeda](https://github.com/dmae3 "Daisuke Maeda")
