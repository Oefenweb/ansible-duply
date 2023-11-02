## duply

[![CI](https://github.com/Oefenweb/ansible-duply/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-duply/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-duply-blue.svg)](https://galaxy.ansible.com/Oefenweb/duply)

Set up [duply](http://duply.net/), a shell front-end for the mighty [duplicity](http://duplicity.nongnu.org/).

#### Requirements

* `duplicity` (will not be installed)

#### Variables

* `duply_version`: [default: `2.2.2`]: Duply [version](https://github.com/Oefenweb/duply/releases) to install
* `duply_install`: [default: `[]`]: Additional packages to install (e.g. `duplicity`)
* `duply_install_dir` [default: `/usr/local/bin`]: Install directory

## Dependencies

None

## Recommended

* `ansible-duplicity` ([see](https://github.com/Oefenweb/ansible-duplicity), when `duply_install` is `[]` or to get the latest version of `duplicity`)

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.duply
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-duply/issues)!
