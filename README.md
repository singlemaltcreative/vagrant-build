SMS vagrant-build
=============

Our vagrant build for provisioning virtual box development environments.

# Here's a handy how-to:

	### *READ FIRST*

	Don't say we didn't warn you: When you use MySQL in a Vagrant virtual machine, you should make absolutely certain that you are backing up your development databases. It might even be a good idea to have MySQL running in "the cloud," or locally on your machine.

## install the latest VirtualBox version for your platform:

	download:
	https://www.virtualbox.org/wiki/Downloads

## install the latest Vagrant version for your platform:

	read as much as your attention span will tolerate:
	http://docs.vagrantup.com/v2/why-vagrant/index.html

	download and install vagrant for your platform:
	http://www.vagrantup.com/downloads	

## if on Windows, install Windows Powershell:

	instructions and download links for you version of Windows:
	(PowerShell is pre-installed on Windows 8+, and Windows Server 2012)
	http://technet.microsoft.com/en-us/library/hh847837.aspx

## create a new directory for your Vagrant projects.
	### for this document, we will use:

	Windows: Users/YOURUSERNAME/Vagrant Projects
	Mac/Linux: HOMEDIRECTORY/Vagrant Projects

	...but you can use anything you want.

## Clone this repository and place it in your "Vagrant Projects" directory

	You might want to delete the .git folder for simplicity's sake, and to avoid confusion later.

## Navigate into your Vagrant Projects folder via the command line (in PowerShell, terminal, etc).

	Run this command:

		vagrant up

	This will automatically take the instructions found in the directory's Vagranftile and provision your server.

