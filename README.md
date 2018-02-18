OpenVPN Server
=========

Configure multiple instances of OpenVPN servers at the same time with multiple clients. Generate all certificates automatically.

Requirements
------------

No requirements.

Role Variables
--------------

See `defaults/main.yml`.

Dependencies
------------

No dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: tobikris.openvpn-server }

License
-------

BSD
