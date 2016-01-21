ansible-java8-oracle
====================

Ansible role to Install the Oracle Java8 webupd8 ppa.

Should work on Ubuntu or Mint. Debian has no ppa suport AFAIK.

Licence is auto-accepted (no prompt) and the whole thing is idempotent
(executing it several times will not do unneeded steps again).

No usage of 'shell:' only ansible commands.


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
```yaml
	- hosts: servers
	  roles:
		- ansible-java8-oracle
```

License
-------
GPL V3, but that is interesting on fork only, you can use it at will.
