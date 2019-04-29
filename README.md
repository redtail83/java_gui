Ansible Role: java_gui
=========

Install GUI library for Java on Ubuntu linux.  
When you run a Java GUI application on Ubuntu linux, you should install additional Java GUI toolkit like libswt-gtk-3-java.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

This role depends on:

* redtail83.x11
* redtail83.adoptopenjdk8_hotspot

Example Playbook
----------------

Ubuntu 16.04:

    - hosts: servers
      roles:
         - { role: redtail83.java_gui }

License
-------

MIT
