ANSIBLE-NETWORK-INTERFACES
======================

This role is metioned for purpose set two or more network interfaces staticly
and have accessible both of them with their IPs. It is not possible cause of
default routing. Here we are using dynamic routing which works well for our
purpose.

Supported and tested OS
-----------------------
- RedHat 7.3


Repositories
------------
This role conts that you already have all necessary repositories for install
NetworkManager-dispatcher-routing-rules package. This package belongs to
RHEL Optional repository.

Usage
-----
Write you own playbook and set all variables for interfaces and overwrite
dictionary from [default variables](./default/main.yml).
