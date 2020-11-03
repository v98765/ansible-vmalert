Ansible Role: VictoriaMetrics vmalert
=========

Deploy and configure [vmalert](https://victoriametrics.github.io/vmalert.html)

Requirements
------------

Ansible

Role Variables
--------------

All variables which can be overridden are stored in defaults/main.yml

Example Playbook
----------------

```text
---
- hosts: vmalert
  connection: ssh
  become: yes
  roles: 
    - ansible-vmalert
```

License
-------

BSD
