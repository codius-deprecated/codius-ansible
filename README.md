# Codius Ansible

Ansible Playbook for building a Codius Host server

## Installation

First install ansible, then download this repository:

````
git clone https://github.com/codius/codius-ansible.git
````

## Usage

First add the target host ip address to the `hosts` file under `[codius-host]`,
then run `ansible-playbook`. Also make sure to add your SSH key from the target
host to the ansible.cfg file.

````
ansible-playbook -i hosts codius-host.yml
````

