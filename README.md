ipsec-tunnel
=========

Configure ipsec-tunnels using strongswan

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

please add your ipsec.conf settings in your ../vars/main.yml before running the role.

Dependencies
------------

VPS should be already been configured with the common role.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: strongswan_ipsec }

License
-------

BSD

Author Information
------------------

ispinosa Jul-2021
