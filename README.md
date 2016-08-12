# Simple NFS Client on Vagrant

This is the Vagrant configuration of a simple NFS client based on CentOS 7.

## Networking
The machine is configured with a bridge network. At the time of creation you may need to identify a host interface to be used as the bridge interface.

## Shared Folder
The variables `mount_point` and `mount_source` (in the [playbook.yml](playbook.yml) file) control the mount.
