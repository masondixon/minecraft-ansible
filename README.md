# minecraft-ansible
Install minecraft 1.10 on an ubuntu server

Pre-reqs
1.  AWS vm or local vm* on a modern ubuntu distribution "ubuntu/trusty64" ( your_version >= v14.* ).
2.  SSH key access to target host ( is easiest but not the ONLY way ).
3.  Ansible installed locally to execute minecraft playbook on target server.

* Vagrant file is for testing locally using vagrant on VBOX virtualization software.

The ansible playbook was modeled after this helpful article which is the manual version of the setup sans ansible. https://www.vultr.com/docs/how-to-install-a-minecraft-server-on-ubuntu
