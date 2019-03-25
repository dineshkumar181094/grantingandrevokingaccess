# grantingandrevokingaccess

groups of server shoud be mentioned in inventory files


example
[servergroup]
sererip   ansible_user=username ansible_ssh_pass=password
 
use command
ansible-playbook code.yml -i inventory --extra-vars "developerid='myid'"-vvvv

copy "ssh_public_key" key value and give to developer

this will give us public key to login in the server 
