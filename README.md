Manage basic packages
=========

Manage (add and/or remove) packages

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

manage_basic_packages_install: []
manage_basic_packages_install_other: []
manage_basic_packages_remove: []
manage_basic_packages_remove_other: []

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: manage_basic_packages}

License
-------


Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
