Role Name
=========

Installation and configuration and Zerotier One.

Role Variables
--------------

- allow_managed: This variable controls whether Ansible is allowed to manage resources on the target system. If set to 1, Ansible is allowed to manage resources. If set to 0, Ansible is not allowed to manage resources.
- allow_global: This variable controls whether Ansible is allowed to access global resources on the target system. Global resources are typically system-wide resources that can affect the behavior of the entire system. If set to 1, Ansible is allowed to access global resources. If set to 0, Ansible is not allowed to access global resources.
- allow_default: This variable controls whether Ansible is allowed to use default settings on the target system. Default settings are typically pre-configured settings that come with the system or a particular software package. If set to 1, Ansible is allowed to use default settings. If set to 0, Ansible is not allowed to use default settings.
- allow_dns: This variable controls whether Ansible is allowed to use DNS resolution on the target system. If set to 1, Ansible is allowed to use DNS resolution. If set to 0, Ansible is not allowed to use DNS resolution. This can be useful in certain scenarios where DNS resolution may not be desirable or available.


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
