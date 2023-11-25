Role Name
=========

Implement bare minumum requirements to deploy and auditd server and configure hosts to forward logs

Role Variables
--------------

roles/audisp-server/vars/main.yml
auditd_port: 1000
auditd_proto: tcp

roles/audisp-client/vars/main.yml
audisp_server: central-logger
auditd_port: 1000

Dependencies
------------

community.general.seport module
#ansible-galaxy collection install ansible.posix

ansible.posix.firewalld module
#ansible-galaxy collection install community.general


Author Information
------------------

nickrov
