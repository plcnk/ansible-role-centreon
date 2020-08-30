Centreon Ansible role
=========

An Ansible role to install Centreon on a virtual machine.

**Important**: This role may need a system restart as the SELinux configuration will be changed.

Requirements
------------

None.

Role Variables
--------------

| Name              | Default     | Description             |
| :---------------- | :---------- | :---------------------- |
| `sql_root_passwd` | `ChangeMe!` | The MySQL root password |

Example Playbook
----------------

  ```YAML
  ---
  - hosts: <group>
    remote_user: <username> # (User should have root privileges)
    become: yes
    become_method: sudo
    roles:
       - centreon
  ```

Support
-------

This role has been tested for the following operating systems:

- CentOS 7.8

Links
-------

- Centreon: <https://www.centreon.com/>

License
-------

BSD 3-Clause.
