Centreon Ansible role
=========

[![Galaxy](https://img.shields.io/badge/galaxy-plcnk.centreon-blueviolet)](https://galaxy.ansible.com/plcnk/centreon) [![GitHub](https://img.shields.io/github/license/plcnk/ansible-role-centreon)](https://github.com/plcnk/ansible-role-centreon/blob/master/LICENSE)

An Ansible role to install Centreon (Central server) on a virtual machine.

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

Additional Information
----------------------

Once the playbook has finished its execution, you can now:

- Reboot your system (recommended).
- Go to [this link](https://docs.centreon.com/20.04/en/installation/web-and-post-installation.html) and follow the post installation instructions.

Links
-----

- Centreon: <https://www.centreon.com/>
