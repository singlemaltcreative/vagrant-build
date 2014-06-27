SMS vagrant-build
=============

Includes:

	-	Ubuntu 12.04.4
	-	Typical LAMP setup
	-	phpmyadmin (more info below)
	-	node.js
	-	grunt.js

Our vagrant build for provisioning virtual box development environments.

# Here's a handy how-to:

### READ FIRST:

Don't say we didn't warn you: When you use MySQL in a Vagrant virtual machine, you should make absolutely certain that you are backing up your development databases. It might even be a good idea to have MySQL running in "the cloud," or locally on your machine. Make sure you plan for this crucial step, lest woes befall you.

## Install the latest VirtualBox version for your platform:

Download:
[https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads)

## Install the latest Vagrant version for your platform:

Read as much as your attention span will tolerate:
[http://docs.vagrantup.com/v2/why-vagrant/index.html](http://docs.vagrantup.com/v2/why-vagrant/index.html)

Download and install vagrant for your platform:
[http://www.vagrantup.com/downloads](http://www.vagrantup.com/downloads)

## If on Windows, install Windows Powershell:

Instructions and download links for you version of Windows:
(PowerShell is pre-installed on Windows 8+, and Windows Server 2012)
[http://technet.microsoft.com/en-us/library/hh847837.aspx](http://technet.microsoft.com/en-us/library/hh847837.aspx)

## Create a new directory for your Vagrant projects.
### For this document, we will use:

Windows: Users/YOURUSERNAME/Vagrant Projects
Mac/Linux: HOMEDIRECTORY/Vagrant Projects

...but you can use anything you want.

## Clone this repository and place it in your "Vagrant Projects" directory

You might want to delete the .git folder for simplicity's sake, and to avoid confusion later.

## Navigate into your Vagrant Projects folder via the command line (in PowerShell, terminal, etc).

Run this command:

	vagrant up

This will automatically take the instructions found in the directory's Vagrantfile and provision your server.

#### You should now be able to access the web root in the browser:

http://127.0.0.1:8888

#### phpmyadmin

http://127.0.0.1:8888/phpmyadmin/
user: vagrant
password: vagrant

#### MySQL Password

user: root
password: vagrant

More information on configuring Vagrant VMs can be found on their website.
