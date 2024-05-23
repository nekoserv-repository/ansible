![ansible](https://repository-images.githubusercontent.com/565076259/4f957f08-4bbf-4e70-bb91-ed09ef847422)

<br />

How to use :

- install : sudo apt install --no-install-recommends ansible

- clone : git clone https://github.com/nekoserv-repository/ansible.git

- update inventory : vi prod

- run examples :
  - ansible-playbook -i prod update.yml
  - ansible-playbook -i prod docker-rebuild.yml
  - ansible-playbook -i prod alpine/ssh-key.yaml
  - ansible-playbook -i prod alpine/upgrade.yml --extra-vars NEW_VERSION="3.20" --limit host.tld
