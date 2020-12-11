# How to create an Ansible Configuration
1. Check if your computer has Ansible using `Ansible --version`
2. Create a configuration file name `ansible.cfg` using vim
3. Insert basic information such as **inventory**, **host verification**, **default remote user**, and **privilege escalation**
4. Save the file

# How to create an Ansible Inventory
1. Check if your **ansible configuration file** has the basic information needed
2. Create a file name inventory using vim
3. Insert IP addresses of your hosts
4. Save the file

# How to create an Ad-hoc Ansible command with setup and shell module
1. Check if your ansible has an **ansible configuration file** and **inventory**
2. Use command `ansible all -m ping` to verify all the hosts 
> If unreachable check if you can enter the hosts via ssh you must configure the inventory file
3. Use command `ansible all -m shell -a "ls"` to see the files of the all the hosts
