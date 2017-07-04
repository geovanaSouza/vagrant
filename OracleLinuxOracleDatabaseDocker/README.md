# Oracle Linux with Oracle Database inside Docker

## Version

* Oracle Linux 7.3
* Oracle Database Standard 12.2.0.1
* Docker (latest)

## Pre-requisites

* Vagrant >= 1.9.5 (https://www.vagrantup.com/downloads.html)
* VirtualBox 5.1.22 (https://www.virtualbox.org/wiki/Downloads)
* Oracle binaries downloaded in docker-images/OracleDatabase/dockerfiles/12.2.0.1 
* Vagrant plugin: vagrant-disksize

## Provision Steps

```
vagrant up
vagrant ssh
```

## Using Docker
* List docker in execution
```
docker ps
```
* List images
```
docker images
```
