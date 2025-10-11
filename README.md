# vyos-ansible-smoketests
Ansible deployment for VyOS smoketests

ansible-playbook main.yml

ansible-playbook main.yml -l r1 -e 'ansible_ssh_host=192.0.2.21'

ansible-playbook main.yml -e 'target_host=r1'

ansible-playbook main.yml --tags show
