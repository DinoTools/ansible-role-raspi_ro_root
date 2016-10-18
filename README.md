Raspberry PI read-only root
===========================

This role deploys some scripts to mount the root filesystem of an Raspberry PI read-only. 

Requirements
------------

* ansible

Role Variables
--------------

    raspi_ro_root_enabled: yes
    raspi_ro_root_state_change_reboot: yes

Dependencies
------------

none

Example Playbook
----------------

    - hosts: servers
      roles:
         - DinoTools.raspi_ro_root

License
-------

MIT

The following files are licensed under the GPLv3 license.
You can download the original files from [rpi-utils](https://github.com/ppisa/rpi-utils).

* files/sbin/init-overlay
* files/sbin/overlayctl
