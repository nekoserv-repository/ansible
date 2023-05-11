![ansible](https://repository-images.githubusercontent.com/565076259/4f957f08-4bbf-4e70-bb91-ed09ef847422)

<br />

How to use :

- install : sudo apt install --no-install-recommends ansible

- clone : git clone https://github.com/nekoserv-repository/ansible.git

- update configuration : vi ~/ansible/cfg/hosts

- run : ansible-playbook -i ~/ansible/cfg/hosts ~/ansible/dns/update.yaml

- another example : ansible-playbook -i ~/ansible/cfg/hosts ~/ansible/dns/upgrade.yaml --extra-vars NEW_VERSION="3.19"
