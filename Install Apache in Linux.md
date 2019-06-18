# Install apache

1) sudo su
2) apt-get update
3) apt-get install apache2

# Check apache2 status

1) service apache2 status

# Checking apache server

1) curl localhost

# Opening default html page

1) cd /var/www/html/
2) ls
3) rm index.html  -> removed
4) vi index.html  -> opened new file
5) We need to be inserted mode to enable editing
6) press escape button for saving
7) :wq -> saving and quiting

# Script Generation

1) sudo su
2) #!/bin/bash
3) apt-get update
4) apt-get install apache2 -y

# Commands

1) lsblk  -> list of devices attached
2) mkfs -t ext4 /dev/xvdf
3) mkdir test  -> creating a folder with name test
4) mount /dev/xvdf test -> entering into the test folder

