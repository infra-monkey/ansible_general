# Ansible Collection infra_monkey.ansible_general
Ansible collection that provide general purpose roles and playbooks

roles:
  - infra_monkey.ansible_general.base_system
  - infra_monkey.ansible_general.postfix_email_client


## add a submodule

git submodule add -b main --name "roles/linux_user" https://github.com/infra-monkey/ansible_role_linux_user.git roles/linux_user

## update a submodule to a new tag

git submodule deinit --all
change tag values
git submodule update --init --recursive