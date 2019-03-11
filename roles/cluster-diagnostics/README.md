Role Name
=========

This role copies the diagnostic tools to the target systems (should be the active elasticsearch master node) and runs them. The result is then copied back to the local system that ran the ansible role

Requirements
------------

Have the current diagnostics.zip in the files folder. No further requirements except SSH access to the master nodes.

Role Variables
--------------

* Inventory should contain the master nodes that the diagnostics are run on.
* Group vars store the credentials to the elastic user, this should be done using vault in the future.

Dependencies
------------

This role is standalone.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

	- hosts: diagnostics
	  roles:
	  	- cluster-diagnostics


License
-------

BSD

Author Information
------------------

Written by https://github.com/Dumbaz
