# node-vagrant-box
Custom Vagrant box for all-things NodeJS related to software stack used in various OSS projects.

## Steps 

```
vagrant init ubuntu/trusty64

vagrant up
Bringing machine 'default' up with 'virtualbox' provider...
==> default: Importing base box 'ubuntu/trusty64'...
==> default: Matching MAC address for NAT networking...
==> default: Checking if box 'ubuntu/trusty64' is up to date...
==> default: Setting the name of the VM: node-vagrant-box_default_1429302166903_24215
...
```

The Vagrant update works that way:
```
==> default: Checking if box 'ubuntu/trusty64' is up to date...
==> default: A newer version of the box 'ubuntu/trusty64' is available! You currently
==> default: have version '14.04'. The latest is version '20150420.1.1'. Run
==> default: `vagrant box update` to update.
```
That's update information is yellow in OS X 10.* console.
