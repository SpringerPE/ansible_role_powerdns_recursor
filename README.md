ansible_role_pwerdns_recursor
=============================

This role automates setting up a PowerDNS caching server using PowerDNS recursor.

Requirements
------------

This role is designed to work on EL6, ~~EL7~~, Debian 7 and Ubuntu 14.04

Role Variables
--------------
Vars are used to set values in the config file for the PowerDNS recursor.
Usable config variables are in defaults/main.yml. For exampe, to configure allow-from you would set powerdns_recursor_allow_from in a var

Dependencies
------------

n.a.

Example Playbook
----------------

tbd



Author Information
------------------

Carsten Hiort (Springer SBM)
