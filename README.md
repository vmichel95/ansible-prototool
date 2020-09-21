vmichel95.gradle
=========

Install [uber/prototool](https://github.com/uber/prototool)

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

> Note: If prototool_installer is toggled between Homebrew (brew) and tar.gz (tgz) mode, please make sure the executable is re-linked if you want to leverage the Homebrew version: `brew unlink prototool && brew link prototool`

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - vmichel95.prototool
```

License
-------

MIT

Author Information
------------------

Victor Michel <victormichel95@gmail.com>