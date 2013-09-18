munin-dovecot
=============

Creates Munin graphs from the stats gathered via `doveadm stats dump` from a [Dovecot](http://dovecot.org/) server running on the same host.

Install
-------

Clone this repository or download the dovecot_ file and create a
symlink as *root* in /etc/munin/plugins by using e.g.:

	cd /etc/munin/plugins; ln -s /path/to/dovecot_ dovecot_<mode>

where <mode> is one of connections (currently only one option).

**Don't forget to restart your munin-node deamon.**
