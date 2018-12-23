# Catalog App Hosting

This work is part of Udacity Full Stack Nanodegree porgram. The purpose of this work is to explore hosting python web app on linux server.

# Hosting Platform

I have create a linux vm hosted in Azure.
Server IP: 104.43.141.177
Server URL: http:// catalog.centralus.cloudapp.azure.com

# Installing Base Dependencies
## Installing Python Packages

```
sudo apt update
sudo apt-get -y install python3 python3-venv python3-dev

```

## Installing Postgresql Database & Create Database User

### Installing Postgresql Packages
```
sudo apt install postgresql postgresql-contrib
```

### Database User Detail

* Database Name: catalog
* Database User: catalog
* Linux User for Catalog DB: catalog

## Installing the Application

```
$ git clone https://github.com/algarni/catalog.git
$ cd catalog
$ pip3 install -r requirements.txt
```

# References

* [How To Install and Use PostgreSQL on Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-18-04)
* [The Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
* [How To Set Up an Apache, MySQL, and Python (LAMP) Server Without Frameworks on Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-an-apache-mysql-and-python-lamp-server-without-frameworks-on-ubuntu-14-04)
* [Deploy Flask & Python3 on Apache2 & Ubuntu](http://terokarvinen.com/2016/deploy-flask-python3-on-apache2-ubuntu)
* [Developping a Flask Web App with a PostreSQL Database – Making all the Possible Errors](https://blog.theodo.fr/2017/03/developping-a-flask-web-app-with-a-postresql-database-making-all-the-possible-errors/)
* [How to Change SSH Port in Ubuntu 18.04](https://www.ubuntu18.com/ubuntu-change-ssh-port/)
* [Ubuntu Server Guide - Firewall](https://help.ubuntu.com/lts/serverguide/firewall.html.en)
* [How to use SSH keys with Windows on Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/ssh-from-windows)