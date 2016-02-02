Tarballs for Ansible Monit
===

[Monit](https://mmonit.com/monit/) is a great OSS utility for managing and monitoring Unix systems.

However, Monit's official download site has too-restrictive rate-limit, and are usually inaccessible via some network routes. For example, try to traceroute from Taipei (via hinet.net) to Stockholm:

[![asciicast](https://asciinema.org/a/23204.png)](https://asciinema.org/a/23204)

To make my Ansible role [williamyeh.monit](https://galaxy.ansible.com/williamyeh/monit/) constantly workable, I copied tarballs from https://mmonit.com/monit/dist/binary/ to this GitHub repo (GitHub is much more reliable and available).  If you have security concerns, feel free to connect directly to official Monit download site.


## Versions

### 5.15

- monit-5.15-linux-x64.tar.gz
  SHA256: [`29427f7be313dee365312389cbb7ff774dfa21f7fe132d74858eda26c4b65e32`](https://mmonit.com/monit/dist/binary/5.15/monit-5.15-linux-x64.tar.gz.sha256)

- monit-5.15-linux-x86.tar.gz
  SHA256: [`2d6f653cd1fb46a9516b2f6714de977e77af17e74c56ec44c03d1674fb1b6671`](https://mmonit.com/monit/dist/binary/5.15/monit-5.15-linux-x86.tar.gz.sha256)

- monit-5.15.tar.gz
  SHA256: [`deada8153dc7e8755f572bc4d790143a92c7a8668dccb563ae4dbd73af56697c`](https://mmonit.com/monit/dist/monit-5.15.tar.gz.sha256)


### 5.14

- monit-5.14-linux-x64.tar.gz
  SHA256: [`25fb07db40665402f70ca5b8c23b38b086f7e4c33eaa1935e36fefcbfb82c927`](https://mmonit.com/monit/dist/binary/5.14/monit-5.14-linux-x64.tar.gz.sha256)

- monit-5.14-linux-x86.tar.gz
  SHA256: [`ce69500576f01586a60677b3980a5664b2b89ee66411a70af5fe186afbd88a9a`](https://mmonit.com/monit/dist/binary/5.14/monit-5.14-linux-x86.tar.gz.sha256)

- monit-5.14.tar.gz
  SHA256: [`d0424c3ee8ed43d670ba039184a972ac9f3ad6f45b0806ec17c23820996256c6`](https://mmonit.com/monit/dist/monit-5.14.tar.gz.sha256)


## License

GNU Affero General Public License (AGPL) V3, as stated in [official Monit site](https://mmonit.com/monit/):

> Monit is free software; you can redistribute it and/or modify it under the terms of the [GNU Affero General Public License](http://www.gnu.org/licenses/agpl.html) (AGPL). The license only applies if you plan to distribute Monit to third parties. In that case, our hope and the reason we use AGPL is that any modification done to Monit can be contributed back so others can benefit. Otherwise, you can do whatever you want with Monit without any restrictions.

For details, see the [COPYING](./COPYING) file, copied from Monit's git source: https://bitbucket.org/tildeslash/monit/
