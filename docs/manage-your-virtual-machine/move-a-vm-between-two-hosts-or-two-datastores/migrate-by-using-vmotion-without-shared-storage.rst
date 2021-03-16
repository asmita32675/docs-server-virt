.. _migrate-by-using-vmotion-without-shared-storage:



===============================================
Migrate by using vMotion without shared storage
===============================================



For vMotion, the VM is located on a datastore that is accessible by
both source and destination hosts. For storage vMotion, the hypervisor
hosting the VM must have access to the source and destination datastore.

*vMotion without Shared Storage* overcomes these constraints by migrating
a VM to a different ESXi host and a different datastore simultaneously.
vMotion without Shared Storage does not require shared objects.

vMotion without Shared Storage is applicable when you want to:

* Migrate a VM between two standalone hypervisors that only have local storage available.
* Migrate between two vSphere clusters where each cluster has a separate
* set of shared datastores.

The following diagram illustrates a vMotion without Shared Storage between
two vSphere clusters. In this case,  a VM and associated vDisk migrate from
one vSphere cluster with one set of shared datastores to another vSphere
with a different set of shared datastores.

.. image:: vsphere-cluster3.png

