# disconnect-ansible 

Sets up disconnect 


## steps for deployment
* install Tailscale
* create a new ssh key (ssh-keygen -o -a 100 -t ed25519 -f ~/.ssh/disconnect)
* load new keys to raspberry (ssh-copy-id -i ~/.ssh/disconnect disconnect@tailscaleIP)
* add new profile to the .ssh/config file on the host machine
* run disconnect.yml playbook
