# Ansible AWX Guide: from scratch to REST API

![Guide Main Image](README_images/awx_logo.png)

A starting  guide contenting 8 parts that instructs AWX end to end usage.

Including:  
- How to deploy Ansible AWX on Docker Compose in CentOS 8;
- Interacting with Ansible AWX REST API to make adjustments in static inventory using tools like tower-cli and curl;
- How to create a workflow in AWX to automates their interactions through playbooks.

**What is Ansible AWX?**

>AWX provides a web-based user interface, REST API, and task engine built on top of Ansible. It is the upstream project for Tower, a commercial derivative of AWX. <sup> [1] </sup>

**What is Red Hat Ansible Tower?**

>Red Hat Ansible Tower <https://www.ansible.com/products/tower> is a web console and REST API for operationalizing Ansible across your team, organization, and enterpise. It’s designed to be the hub for all of your automation tasks. <sup> [2] </sup>

[1]: <https://github.com/ansible/awx>
[2]: <https://docs.ansible.com/ansible/latest/reference_appendices/tower.html>

**Why Ansible AWX?**

- Ansible is Simple, Powerful and Agentless;
- AWX provides an automation solution;
- Takes control across distributed teams and organizations;
- Uses individual credentials to execute playbooks;
- Audits and reports automation and management activity.

## Topics

1. [Operating System Installation: CentOS 8](1_os_install.md)
2. [AWX Installation on Docker Compose](2_awx_install.md)
3. [Managing AWX using REST API, CLI and Web UI](3_awx_cli.md)
4. [Playbook to automate AWX REST API interactions](4_playbook.md)
5. [Creating a remote user for Ansible](5_createuser.md)
6. [AWX Workflow Use Case](6_workflow.md)
7. [Protecting data using Ansible Vault](7_vault.md)
8. [What's Next](8_whatsnext.md)

## Continue Reading

Next topic: [Operating System Installation: CentOS 8](1_os_install.md)

## License

Creative Commons - Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)  
[![Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-nc.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

## Author Information

This guide was created in 2019 by [Cláudio Domingos](https://linkedin.com/in/cadomingos)
