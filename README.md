Role Name
=========

Installs a WildFly Instance with default configuration.

Requirements
------------

A CentOS 7 running.

Role Variables
--------------

JAVA_OPEN_JDK: Open JDK package name.

WILDFLY_VERSION: WildFly Version to be Downloaded.

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

---
- hosts: wildfly
  name: Install WildFly Application Server

  roles:
    - smsilva.ansible-wildfly

License
-------

BSD
