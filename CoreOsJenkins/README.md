# CoreOs with Jenkins Vagrant box

## Version

* CoreOs stable (https://coreos.com/releases/)
* Jenkins

## Pre-requisites

* Vagrant >= 1.9.1 (https://www.vagrantup.com/downloads.html)
* VirtualBox (https://www.virtualbox.org/wiki/Downloads)
* Vagrant Plugin: vagrant-winnfsd
(```vagrant plugin install vagrant-winnfsd```)


## Provision Steps

```
vagrant up
vagrant ssh
```

## Accessing Jenkins
* Insert the line bellow in your hosts file:
```
10.10.10.10 jenkins.local.com.br
```

## Plugins required
* Git Plugin
* TimeStamper Plugin
* Workspace Cleanup Plugin
* Environment Injector Plugin
* Mask Passwords Plugin
* Simple Theme Plugin
* Hudson Post build task
* Email Extension Plugin	
