# Changelog

All changes will be documented in this file.

## 1.0.1 (September 01, 2020)

### Changed

- Changed `LICENSE` to **MIT**.
- Changed Issue Tracker URL in [meta/main.yml](https://github.com/plcnk/ansible-role-centreon/blob/master/meta/main.yml) to the GitHub repository.

## 1.0.0 (September 01, 2020)

### Added

- Added playbook testing with Molecule and Travis CI.

### Changed

- Edited `README.md` to add badges.

### Fixed

- Fixed yamllint errors.

## 0.1.2 (August 30, 2020)

### Changed

- Edited role description.
- Edited [README.md](https://gitlab.com/plcnk-public/ansible/centreon/-/blob/master/README.md).

## 0.1.1 (August 30, 2020)

### Changed

- Changed role name and author for Ansible Galaxy.

### Fixed

- Removed trailing whitespaces.

### Removed

- Removed unnecessary `setenforce 0` command task in [tasks/permissions.yml](https://gitlab.com/plcnk-public/ansible/centreon/-/blob/master/tasks/permissions.yml) as it is already done with the `selinux` module.

## 0.1 (August 30, 2020)

### Added

- Initial project release.
