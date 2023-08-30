In this Attune Blueprint, we'll automate the process of 
provisioning a Red Hat Enterprise Linux 9 (RHEL 9) machine with 
BIOS boot using Kickstart on VMware ESXi. 

Automating the deployment of operating systems is a critical 
aspect of modern IT infrastructure management.

The Kickstart method is a powerful tool that allows system 
administrators to streamline the installation of Red Hat 
Enterprise Linux (RHEL) on virtual machines (VMs) running on 
VMware ESXi. 

## Understanding Kickstart Automation

Kickstart simplifies the installation of RHEL by using a 
configuration file that provides instructions for various 
installation settings. These settings range from language 
preferences to disk partitioning and package selection. By 
automating these settings, Kickstart eliminates the need for 
manual intervention during the installation process, making it a 
valuable time-saving tool.

## The Need for BIOS Boot on ESXi

VMware ESXi is a hypervisor that enables the virtualisation of 
multiple guest VMs on a single physical server. In scenarios 
where BIOS boot is required instead of the more modern UEFI boot, 
the Kickstart automation process can be tailored to accommodate 
these requirements. BIOS boot is often preferred for compatibility 
with legacy systems or certain configurations.
