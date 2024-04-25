
# Ansible 

To get a working development enviroment to fit your needs follow these commands and you can get started by developing your first ansible module / playbook.

## Activate Python virtual enviroment

    python3 -m venv ansible_venv
    source ansible_venv/bin/activate
Now the virual enviroment should be activated now we need to install the required packages and dependencies

    pip3 install pywinrm
    pip3 install pyVim
    pip3 install pvvmomi
    pip3 install netaddr
    pip3 install jmespath
    pip3 install ansible
    pip3 install ansible-lint
    ansible-galaxy collection install ansible.windows
    ansible-galaxy collection install community.general
    ansible-galaxy collection install community.vmware
