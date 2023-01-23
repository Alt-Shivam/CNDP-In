# CNDP-In

## Install ninja 
```
sudo apt-get -y install ninja-build
```

## Install Ansible 
```
sudo apt install ansible
```

## Start Ansible playbook
```
ansible-playbook -i hosts.ini localhost-kernel-install.yml
```

## Reboot the host
```
sudo reboot now
```

## Start post kernel update ansible playbook
```
ansible-playbook -i hosts.ini localhost-post-kernel-install.yml
```

## Make
```
make
```
## Run Helloworld program
```
./builddir/examples/helloworld/helloworld
```
