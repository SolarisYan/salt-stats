salt-stats
==========

A collection of modules for collecting stats

Usage
-----

Clone the repo to your Salt master and adjust `file_roots` in `/etc/salt/master`.

```
file_roots:
  base:
    - /srv/salt
    - /path/to/salt-stats/salt
```