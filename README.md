# ansible-monitoring-inventories
This repository contains all the inventories and all the files needed by VMs that will be built with the playbook "ansible-monitoring"

It has to be used with the "ansible-monitoring" repository to complete the "Ansible Playbook" that installs and configures several monitoring tools.

To get the Playbook working it is needed to run the commands below and change what you need under 'inventories' directory:

   * ```cd /opt/ ; git clone https://github.com/[malavolti|ConsortiumGARR|GEANT]/ansible-monitoring.git```
   * ```cd /opt/ansible-monitoring ; git clone https://github.com/[malavolti|ConsortiumGARR|GEANT]/ansible-monitoring-inventories inventories```
