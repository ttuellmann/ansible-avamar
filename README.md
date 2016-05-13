# ansible-avamar

This will be a collection of ansible playbooks to manage large Avamar
environments with a focus on VMware Image Proxies.

## patch-proxy

This role installs Avamar OS security patches in an automated manner. You need
to download the current ISO image and md5sum file from EMC support and put them
into one folder. Copy playbooks/proxy-patch.yml.example and configure the
correct release and path.

This was only tested on 7.2 proxies but should work on all 7.x releases. Use at your own risk!

TODO: This lacks a lot of error handling and proper tests.
