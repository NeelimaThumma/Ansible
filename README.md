# Ansible
Ansible is Declarative , can scale to large infra structure.

Ansible uses SSH Protocal. Ansible Need Inventory .

How Ansible connects and Manages Nodes ?
Earlier Modules , Latest after 2.9 version Uses collections.

Collections is group of Modules.

List of collections : Install collection , File Collection, service collection.

Example: Install Nginix server, configure configuration, start nginx service
Ansible playbook is wrriten in YAML markup language -Ex: playbook.yml  has  Lists, MAP/Dictionary .


Some of the most commonly used modules in ansible are :
	ansible.builtin.yum:
	ansible.builtin.debug:
  ansible.builtin.replace
	ansible.builtin.copy
	ansible.builtin.file
	ansible.builtin.systemd
	ansible.builtin.unarchive
	ansible.builtin.shell
	ansible.builtin.import_role
	ansible.builtin.dnf












