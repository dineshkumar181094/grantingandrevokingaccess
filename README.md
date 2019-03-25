# grantingandrevokingaccess

groups of server shoud be mentioned in inventory files


example
[servergroup]
sererip   ansible_user=username ansible_ssh_pass=password
 
use command
ansible-playbook code.yml -i inventory --extra-vars "developerid='myid'"-vvvv

default password is "P@ssw0rd"

this will give us public key to login in the server 
