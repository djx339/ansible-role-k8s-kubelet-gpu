Ansible Role: kubernetes kubelet gpu support
=========

Configure kubelet to support NVIDIA GPU.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```yml
- hosts: all
  roles:
    - { role: djx339.k8s-kubelet-gpu }
```

License
-------

BSD

Author Information
------------------

This role was created by [Daniel D](https://github.com/djx339).
