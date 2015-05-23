# techo-vagrant

##Install

* Ensure you have the latest version of VirtualBox and Vagrant installed on you machine:
* Now cd into techo-vagrant project
```bash
cd ~/Documents/workspace/techo-vagrant
```
* Log into vagrant cloud vagrant login User janbarta/***** as username/password.
* Add vagrant box 
```bash
vagrant box add janbarta/ubuntu-mongo-node-nginx
```
* Initialise Vagrant environment vagrant 
```bash
init janbarta/ubuntu-mongo-node-nginx
``` 
* This will create a Vagrantfile
* Replace Vagrantfile with Vagrantfile_sample. You can do this by typing `cp Vagrantfile_sample Vagrantfile`
* Edit new Vagrantfile change path to techo folder



