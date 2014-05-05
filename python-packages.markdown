# Python Packages

## Tools

- [pip](http://www.pip-installer.org/)
- [curdling](http://clarete.li/curdling/) -- asynchronous operation with cache
  support.

## Configuration

Inside `~/.pip/pip.conf`:

    [global]
    default-timeout = 60
    respect-virtualenv = true
    download-cache = /home/turicas/.pip/cache
    log-file = /home/turicas/.pip/pip.log

> `~/.pip/cache` directory should exists.
