Role Name
=========

Sets up SSH key

Role Variables
--------------

- sshkey path to public key
- newuser remote username

Example Playbook
----------------

How to use role:

    - hosts: servers
      roles:
         - { role: ysz.ssh-with-keys, sshkey: /path/to/id_rsa.pu, newuser: buildbot }

License
-------

BSD
