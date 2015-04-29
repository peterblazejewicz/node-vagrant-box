# node-vagrant-box
Custom Vagrant box for all-things NodeJS related to software stack used in various OSS projects.

## Steps

```shell
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
```shell
==> default: Checking if box 'ubuntu/trusty64' is up to date...
==> default: A newer version of the box 'ubuntu/trusty64' is available! You currently
==> default: have version '14.04'. The latest is version '20150420.1.1'. Run
==> default: `vagrant box update` to update.
```
That's update information is yellow in OS X 10.* console

```shell
vagrant@vagrant-ubuntu-trusty-64:/srv/www/hackathon-starter$ nodemon app.js
29 Apr 20:22:16 - [nodemon] virtual machine clock offset: 00h06m08s
29 Apr 20:22:16 - [nodemon] v1.3.7
29 Apr 20:22:16 - [nodemon] to restart at any time, enter `rs`
29 Apr 20:22:16 - [nodemon] watching: *.*
29 Apr 20:22:16 - [nodemon] starting `node app.js`
Express server listening on port 3000 in development mode
GET / 200 797.121 ms - -
GET /api 200 213.111 ms - -
GET / 200 167.348 ms - -
```
![Hackhaton Starter running on the Vagrant box](https://cloud.githubusercontent.com/assets/14539/7400678/de6c92fc-eebe-11e4-94e8-dd740ca91029.jpg)
