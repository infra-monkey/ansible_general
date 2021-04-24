# Ansible Collection infra_monkey.ansible_general
Ansible collection that provide general purpose roles and playbooks

roles:
  - infra_monkey.ansible_general.base_system
  - infra_monkey.ansible_general.postfix_email_client
  - infra_monkey.ansible_general.linux_user
  - infra_monkey.ansible_general.zabbix_agent
  - infra_monkey.ansible_general.postgresql_backup


## add a submodule

    git submodule add -b main --name "roles/linux_user" https://github.com/infra-monkey/ansible_role_linux_user.git roles/linux_user

## update a submodule to a new tag

    cd roles/linux_user
    git pull
    git checkout <tag>
    cd ../..
    git commit "update to tag <tag>
    git push