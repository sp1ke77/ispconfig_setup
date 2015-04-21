# README #

[![PayPayl donate button](https://www.paypalobjects.com/it_IT/IT/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=TB4Q3UJDC5JDJ "Help US support this project using Paypal")

# Version #
v.1.0.6

This is a system to automate the installation of ISPConfig 3 
control Panel ( http://www.ispconfig.org/page/home.html ).

Tested on:
- Debian 7 (VmWare Esxi, Amazon AWS, Virtualbox)
- ISPConfig 3.0.5.4p5

For now it is tested and developed only on Debian systems.

Maybe it works well also on Ubuntu systems.

### What is this repository for? ###

This repository contains some scripts for the automation

of installation of ISPConfig 3 control panel.

For now it's composed of two main scritps

- install.sh = is the main scritps wich will do a default install
		       based on the https://www.howtoforge.com/perfect-server-debian-wheezy-apache2-bind-dovecot-ispconfig-3
                       and to fix some issue on normal installation files, provided by debian repository

You can Choose during install:
- Apache / Nginx
- Dovecot or Courier
- Quota On/Off
- Jailkit On/Off
- Squirrelmail / Roundcube

### How do I get set up? ###

* Summary of set up

First of all follow the guide 

https://www.howtoforge.com/perfect-server-debian-wheezy-apache2-bind-dovecot-ispconfig-3

to install debian as required for ISPConfig

* Configuration

After you got a fresh and perfect Debian installation you had to

```shell
apt-get -y install unzip
wget https://github.com/servisys/ispconfig_setup/archive/master.zip
unzip master.zip
cd ispconfig_setup-master
./install.sh
```

Follow the instruction on the screen

### Who had contributed to this work? ###

* The scripts and instructions have been produced by Matteo Temporini ( <temporini.matteo@gmail.com> )
* Special thanks to Torsten Widmann for contribution to the code
* The code is based on the "Automatic Debian System Installation for ISPConfig 3" of Author: Mark Stunnenberg <mark@e-rave.nl>
* Howtoforge community https://www.howtoforge.com/community/
