ubuntu_python_apt
========

Idempotent installer for python-apt module (prevents "python-apt is not installed" errors).  

If you're enocountering systems without python-apt installed, this thing is super easy and will prevent those errors by checking for the presence of the python-apt package and instlaled it with idempotence.  Just include it or make this role a dependency of your apt* roles.  

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

License
-------

Apache v2.0

Author Information
------------------

[Paul Durivage](mailto:pauldurivage+git@gmail.com)