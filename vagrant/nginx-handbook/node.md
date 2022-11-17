# https://www.freecodecamp.org/news/the-nginx-handbook/
## this folder container Vagrantfile used to create the virtual machine
### vagrant up
### vagrant status
### vagrant ssh nginx-handbook-box
### http://192.168.20.20
### to stop the virtual machine
#### vagrant halt
### to destroy the virtual machine
#### vagrant destroy

## Install NGINX on a Provisioned Server or Virtual Machine
### sudo apt update && sudo apt upgrade -y
### sudo apt install nginx -y
### sudo systemctl status nginx
### sudo systemctl start nginx (incase service not running)