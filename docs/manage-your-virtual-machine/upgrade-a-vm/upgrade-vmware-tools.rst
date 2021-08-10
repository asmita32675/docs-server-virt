.. _upgrade-vmware-tools:

====================
Upgrade VMware Tools
====================

VMware Tools provides OS drivers for virtual hardware and enables
features such as vRAM ballooning and the graceful shutdown of the OS
in the Rackspace Technology Customer Portal. vRAM ballooning is a
memory reclamation technique that can negatively affect performance.

Occasionally, you need to upgrade VMware Tools. Upgrading VMware Tools
can provide additional functionality, update drivers, and address known
issues. A new VMware Tools version usually coincides with an ESXi release.
If you have configured your VM to automatically reboot during a
VMware Tools upgrade, ensure that you have scheduled the update for
hours outside your peak hours.

To upgrade VMware Tools, open a Rackspace Technology ticket and specify
the VM that contains the VMware tools that you want to upgrade. The host
determines the upgraded version.

