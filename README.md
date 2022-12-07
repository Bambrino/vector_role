Role Name
=========

Simple role for vector.

Requirements
------------

CentOS7

Role Variables
--------------

<table>
  <tr>
    <td>Variable name</td>
    <td>Default value</td>
    <td>Description</td>
  </tr>
  <tr>
    <td>vector_version</td>
    <td>"0.22.2"</td>
    <td>Vector version</td>
  </tr>
  <tr>
    <td>vector_arch</td>
    <td>"x86_64"</td>
    <td>Arch type</td>
  </tr>
</table>

Dependencies
------------

Yum packet manager required

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vector-role, vector_version: "0.22.2", vector_arch: "x86_64" }

License
-------

BSD

Author Information
------------------

Bambrino
