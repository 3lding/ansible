Ansible Role CoreOS Kubernetes 
=========

This role configures your fedora CoreOS host for Kubernetes Cluster Role


Requirements
------------

Pre-installed fedora CoreOS host with basic functionality

Role Variables
--------------

There are variables for configuring some sysctl parameters. You have to ensure that they match with your network interface names.

Example Playbook
----------------

Create a simple file called 'run.yml' and add these simple lines:

    - hosts: servers
      roles:
         - fedora_coreos 

Author Information
------------------

GitHub: https://github.com/Balthyr
