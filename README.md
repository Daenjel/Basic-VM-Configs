# Basic-VM-Configs
Getting started with Virtual Machines

# Creating VMs

Virtual machines are usually created from a template. Users can also create blank virtual machines. A blank virtual machine is a virtual machine without an OS template. Users can attach an ISO file and install the OS from the CD/DVD-ROM.

Note

You can create a VM without starting it. You can determine whether the VM needs to be started as part of the VM deployment. A request parameter, startVM, in the deployVm API provides this feature. For more information, see the Developer’s Guide.

To create a VM from a template:

    Log in to the CloudStack UI as an administrator or user.

    In the left navigation bar, click Instances.

    Click Add Instance.

    Select a zone.

    Select a template, then follow the steps in the wizard. For more information about how the templates came to be in this list, see *Working with Templates*.

    Be sure that the hardware you have allows starting the selected service offering.

    Click Submit and your VM will be created and started.

    Note

    For security reason, the internal name of the VM is visible only to the root admin.

To create a VM from an ISO:

Note

(XenServer) Windows VMs running on XenServer require PV drivers, which may be provided in the template or added after the VM is created. The PV drivers are necessary for essential management functions such as mounting additional volumes and ISO images, live migration, and graceful shutdown.

    Log in to the CloudStack UI as an administrator or user.
    In the left navigation bar, click Instances.
    Click Add Instance.
    Select a zone.
    Select ISO Boot, and follow the steps in the wizard.
    Click Submit and your VM will be created and started.

