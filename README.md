# techsauce-playbook
Playbook to automate setting up Wordpress

Instructions:
1. Edit the `hosts`file and put in the IP address of where you want to install WordPress. The tested OS was Ubuntu 16.04
2. Make sure you have `ansible` installed on your machine
3. Then to automate WordPress installation, simply run this commmand in the cloned repository:
```
ansible-playbook playbook.yml -i hosts -u root --ask-pass
```

Ref: https://dotlayer.com/how-to-use-an-ansible-playbook-to-install-wordpress/
