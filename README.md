# Vagrant Node Developer Workstation.

Simple vagrant script for creating a development environment for a bearbones Vagrant box for
Node.js  web application development.

Based from:
ubuntu/trusty64 box

Installs:
# Using Ubuntu


curl -sL https://deb.nodesource.com/setup_0.10 | sudo -E bash -
sudo apt-get install -y nodejs
at this point you should also have NPM 

To downgrade or upgrade version of  depending on what your current enviornement is
sudo npm cache clean -f
sudo npm install -g n
sudo n 4.4.2


To install individual modules use NPM as usual or SUDO commands
i.e. for instance with sudo and specifying a version
sudo npm install express@3.5.0
(@3.5.0 indicating the version)

**line 46 of vagrant file indicating synched folder setup
need to create on your local machine a folder myMEANApp
to place and run files you create


## Create Vagrant machine
```Bash
vagrant up
vagrant ssh
```
## Web App Development
```Bash
cd /vagrant/myMEANApp
node and the specific file you want to run
```
## Destroy Server
`vagrant destroy`
