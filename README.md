# Vagrant Node Developer Workstation.

Simple vagrant script for creating a development environment for Appitur web and mobile applications.

Based from:
ubuntu/trusty64 box

Installs:

sudo npm install express@3.5.0


line 46 of vagrant file indicating synched folder setup
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
npm run dev
```
## Destroy Server
`vagrant destroy`
