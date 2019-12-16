# Ansible AWX Guide: from scratch to REST API (1/8)

## Operating System Installation: CentOS 8

Before installing Ansible AWX, we have to install the Operating System.

CentOS is a great open source RedHat-like community operating system.

## Table of Contents

- [Concepts](#Concepts)
- [System Requirements](#System-Requirements)
- [Download CentOS ISO](#Download-CentOS-ISO)
- [Installing CentOS](#Installing-CentOS)
- [Summary](#Summary)
- [References](#References)

### Concepts

#### What is CentOS

>The CentOS Project is a community-driven free software effort focused on delivering a robust open source ecosystem around a Linux platform.  
We offer two Linux distros:  
– CentOS Linux is a consistent, manageable platform that suits a wide variety of deployments. For some open source communities, it is a solid, predictable base to build upon.  
– The new CentOS Stream is a rolling-release distro that tracks just ahead of Red Hat Enterprise Linux (RHEL) development, positioned as a midstream between Fedora Linux and RHEL. For anyone interested in participating and collaborating in the RHEL ecosystem, CentOS Stream is your reliable platform for innovation. <sup>[1]</sup>

### System Requirements

- 20GB disk space;
- 4GB of memory (AWX on Docker Compose requires at least 4GB).

A detailed system requirements <sup>[2]</sup> is provided from CentOS documentation.

### Download CentOS ISO

Download the [CentOS ISO].

[CentOS ISO]: <https://www.centos.org/download/>

![Download ISO File](1_os_install_images/download_iso.png)

### Installing CentOS

Boot your machine with the previous CentOS ISO file.

#### Initial Screen

Select "Install CentOS Linux..."
![Initial Screen](1_os_install_images/install_start.png)

#### Select Language

Configure the system language.
![Select Language](1_os_install_images/install_select_language.png)

#### Select _"Installation Destination"_

Configure the file system layout.
![Select Destination](1_os_install_images/install_select_destination.png)

For the bellow screen, there is no modifications, then click **[Done]**
![Select Partition](1_os_install_images/install_select_destination_partition.png)

#### Select _"Network & Host Name"_

Configure network settings.
![Select Network](1_os_install_images/install_select_network.png)

#### Define _"Host Name"_

Configure Host Name, click **[Apply]**
![Setup hostname](1_os_install_images/install_select_network_hostname.png)

#### Setup _"NAT NIC"_

Configure the NAT Network (internet access) using DHCP.
![Setup NAT NIC](1_os_install_images/install_select_network_setup_nat_dhcp.png)
![Setup NAT NIC Enable Boot](1_os_install_images/install_select_network_setup_nat_dhcp_enableboot.png)

#### Setup _"Private NIC"_

Configure the Private Network (host-only) using static IP address.
![Setup Private NIC](1_os_install_images/install_select_network_setup_private_static.png)
![Setup Private NIC Enable Boot](1_os_install_images/install_select_network_setup_private_enableboot.png)
![Setup Private NIC Summary](1_os_install_images/install_select_network_setup_private_summary.png)

#### Select _"Software Selection"_

Configure the software profile for this installation.
![Select Software](1_os_install_images/install_select_software.png)
![Select Software Selection](1_os_install_images/install_select_software_selection.png)

#### Select _"Time & Date"_

Configure region.
![Select Timezone](1_os_install_images/install_select_timezone.png)
![Select Timezone Region](1_os_install_images/install_select_timezone_region.png)

#### Installation Preview

In *Installation Summary*, click **[Begin Installation]**
![Installation Summary](1_os_install_images/install_summary.png)

#### Installation Running

![Installation Running](1_os_install_images/install_running.png)

#### Select _"Root Password"_

Set root password.
![Select Root Password](1_os_install_images/install_select_rootuser.png)
![Select Root Password](1_os_install_images/install_select_rootuser_password.png)
![Select Root Password Confirm ](1_os_install_images/install_select_rootuser_password_confirm.png)

#### Installation Summary

Once your installation is done, click **[Reboot]**
![Installation Reboot](1_os_install_images/install_reboot.png)

### Summary

In this topic was presented:

- Installing CentOS 8 operating system.

### References

[1]: <https://www.centos.org>
\[1\] - <https://www.centos.org>

[2]: <https://wiki.centos.org/About/Product>
\[2\] - <https://wiki.centos.org/About/Product>

## Continue Reading

Next topic: [AWX Installation on Docker Compose](2_awx_install.md)

[Go to main page](README.md)

[Go to top](#Operating-System-Installation-CentOS-8)
