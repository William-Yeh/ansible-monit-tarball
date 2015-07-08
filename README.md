Tarballs for Ansible Monit
===

[Monit](https://mmonit.com/monit/) is a great OSS utility for managing and monitoring Unix systems.

However, Monit's official download site has too-restrictive rate-limit, and are usually inaccessible via some network routes.

To make my Ansible role [williamyeh.monit](https://github.com/William-Yeh/ansible-monit) constantly workable, I copied tarballs from https://mmonit.com/monit/dist/binary/ to this GitHub repo (GitHub is much more reliable and available).  If you have security concerns, feel free to connect directly to official Monit download site.



## License

GNU Affero General Public License (AGPL) V3, as stated in [official Monit site](https://mmonit.com/monit/):

> Monit is free software; you can redistribute it and/or modify it under the terms of the [GNU Affero General Public License](http://www.gnu.org/licenses/agpl.html) (AGPL). The license only applies if you plan to distribute Monit to third parties. In that case, our hope and the reason we use AGPL is that any modification done to Monit can be contributed back so others can benefit. Otherwise, you can do whatever you want with Monit without any restrictions.

For details, see the [COPYING](./COPYING) file, copied from Monit's git source: https://bitbucket.org/tildeslash/monit/