# provnas
Ansible provisionsing of jails in a freenas environment

This project aims at creating ansible glue for freenas servers as well as ready-to-use roles for most common jails that are not in the list of plugins.
The glue is in draft stage ("works for me") and will be generalized if there is interest in use.

## Features
### Ansible modules
Modules use freenas API
* freenas_jail
  * create, destroy, start, stop, restart jails
* freenas_mountpoint 
  * create, delete mountpoint assignments of a jail

### Roles
* musicbrainz
  * setup a musicbrainz server
  * download, configure, download dump, import dump
* proxy
  * setup and configure squid

## Installation

## Usage


