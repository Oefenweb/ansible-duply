## duply

[![Build Status](https://travis-ci.org/Oefenweb/ansible-duply.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-duply) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-duply-blue.svg)](https://galaxy.ansible.com/list#/roles/3585)

Set up [duply](http://duply.net/), a shell front-end for the mighty [duplicity](http://duplicity.nongnu.org/).

#### Requirements

* `duplicity` (will not be installed)

#### Variables

* `duply_install`: [default: `[]`]: Additional packages to install (e.g. `duplicity`)
* `duply_install_dir` [default: `/usr/local/bin`]: Install directory

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
  - duply
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-duply/issues)!
