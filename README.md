
# Linux Server Configuration

This is the sixth project of the [Full Stack Web Developer Nanodegree](https://in.udacity.com/course/full-stack-web-developer-nanodegree--nd004/?). 

The objective is to turn a brand-new, bare bones, Linux server into the secure and efficient web application host your applications need.

## Software requirements:
* python 2.7
* linux ubuntu 16.04

##  Apps:
* ufw
* openssh
* uWSGI
* flask
* python
* nginx
* postgresql
* psycopg2
* virtualenv
* pip
* git

## Installation Information:
* IP: 52.90.242.93
* Users: ubuntu grader
* URL: linuxdeploy.scscn.org


## Configurations:
* modified /etc/ssh/sshd_config.
* modified ufw.
* modified postgres db, createdb and change password.
* add uwsgi and wsgi.ini and appliation systemctl service.
* modified and link nginx cofigurations.
* ssh port change from 22 to 2200

## 3rd Party Resources:
* SSH configuration [SSH how to](https://www.ssh.com/ssh/sshd_config/)
* UFW firewall [UFW setup](https://www.digitalocean.com/community/tutorials/how-to-setup-a-firewall-with-ufw-on-an-ubuntu-and-debian-cloud-server)
* Setup flask uswgi nginx [Flask uswgi and nginx](https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-uwsgi-and-nginx-on-ubuntu-16-04)
* Flask uwsgi secret_key not set [Flask secret_key solutions](https://stackoverflow.com/questions/26080872/secret-key-not-set-in-flask-session)

