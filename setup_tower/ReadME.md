---

# Instructions

1) Clone this repo into the host server/computer:

    git clone git@github.com:Zwani/sys_admin_work.git

    cd sys_admin_work
    
    cd setup_tower

2) Make sure ansible is installed:

    pip3 install ansible

3) Create a file "inventory.ini" in the same directory as this one and configure it

4) Create a file "ansible.cfg" for more configurations

5) Make you have the awx-operator cloned in the host's destination, for example:

    git clone git@github.com:ansible/awx-operator.git

6) Indicate the path of the awx-operator directory in "myvars.yml", for example:

    destination_path: "home/jonny/Desktop"


6) run the main.yml task, for example:

    ansible-playbook main.yml
