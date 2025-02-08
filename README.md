google_chrome
==========
[![Ansible Lint](https://github.com/oxivanisher/role-google_chrome/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-google_chrome/actions/workflows/ansible-lint.yml)

Install Google Chrome.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Install Chrome
  hosts: ubuntu
  roles:
    - role: oxivanisher.linux_desktop.google_chrome
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_desktop](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_desktop/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_desktop).
