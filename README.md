Role Name
=========

Implement bare minumum requirements to deploy and auditd server and configure hosts to forward logs

SSL/TLS configuration not included

Role Variables
--------------

roles/audisp-server/vars/main.yml


roles/audisp-client/vars/main.yml


Dependencies
------------

-- community.general.seport module --

ansible-galaxy collection install ansible.posix

-- ansible.posix.firewalld module --

ansible-galaxy collection install community.general


Author Information
------------------

nickrov
