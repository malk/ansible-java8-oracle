ansible-java8-oracle
====================

Ansible role to Install the oracle Java8 webupd8 ppa.

Should work on ubuntu or mint, I tested it on trusty, Debian has no ppa suport AFAIK.

Licence is auto-accepted (no prompt) and the whole thing is idempotent
(executing it several times will not do unneeded steps again).

Only usage of 'shell:' was to accept the licence itself (using 'created:' to be idempotent).


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
GPL V3, but that is interesting on frok only, you can use it at will
