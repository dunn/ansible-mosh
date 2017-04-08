ansible-mosh
============

Compile and install mosh-server on Fedora/EL.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - { role: dunn.mosh, become: yes }

```

License
-------

MIT
