# provnas
Ansible provisionsing of jails in a freenas environment

This project aims at creating ansible glue for freenas servers as well as ready-to-use roles for most common jails that are not in the list of plugins.

Features
========
Ansible modules
* freenas_jail to create, destroy, start, stop, restart jails via the freenas API
* freenas_mountpoint to create, delete mountpoint assignments of a jail via the freenas API

Roles
* musicbrainz to setup, configure, download dump of a musicbrainz server
* proxy to setup, configure squid

Usage
=====
 
