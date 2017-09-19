**Libvirt Detach GPU**

This is a branch of the Libvirt hotplug USB plugin.  This plugin is meant to detatch PCI devices, specifically GPUs before killing a VM.  Many AMD GPUs do not properly shutdown when the VM is killed, creating issues for future use.
