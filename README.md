# Ansible Collection infra_monkey.ansible_general
Ansible collection that provide general purpose roles and playbooks

roles:
  - infra_monkey.ansible_general.base_system
  - infra_monkey.ansible_general.postfix_email_client


## update a submodule to a new tag
> cd roles/base_system
>
> git checkout 0.0.2
>
> cd ../..
>
> git add roles/base_system
>
> git commit -m "moved base_system to tag 0.0.2"
>
> git push
>
or
> git submodule set-branch -b 0.0.2 roles/base_system
>
> ( git submodule init )
>
> git submodule update
>