Manage basic packages
=========

Manage (add and/or remove) packages

Role Variables
--------------

`manage_basic_packages_install`: []

`manage_basic_packages_install_other`: []

`manage_basic_packages_remove`: []

`manage_basic_packages_remove_other`: []

Example Variables
-----------------

    manage_basic_packages_install:
      - mc
      - htop
      - jq

    manage_basic_packages_remove:
      - nmap

If you need to add and/or remove additional packages that are not needed for all machine packages, 
but only for a group or a separate machine, use the variables    
`manage_basic_packages_install_other`    
and    
`manage_basic_packages_remove_other`  

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

Vladimir Zhurkin 

 ansible@icce.im
