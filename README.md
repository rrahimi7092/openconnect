# openconnect

## Install 
Test OS : Ubuntu 18 - 20 - 22
```
sudo apt-add-repository ppa:ansible/ansible
```
```
sudo apt install ansible
```
```
sudo apt install git
```
```
git clone https://github.com/rrahimi7092/openconnect.git
```
```
cd openconnect
```
```
ansible-playbook -i inventory/hosts myproject.yml
```

# Add User
```
ansible-playbook -i inventory/hosts myproject.yml --tags add_user
```
