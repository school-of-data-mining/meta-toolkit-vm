# [Meta-toolkit](https://meta-toolkit.org/) VM setup

## Requirements:
- VirtualBox
- Vagrant
- ansible-playbook

## How to 

First of all we clone this repo.

 1. Open *Vagrantfile* and define how you will to map your host folders with text-mining data on a VM
    
    mount_path = { host: "/your/host/path",
                      vm: "/your/vm/path"}

 2. run **vagrant up**  and you are done with VM. (but be patient it can take some time)

 3. to login in VM with **vagrant ssh** 

 4. you find meta-toolkit in an **/opt/meta** folder 

 

