# Dokku - AWS Tutorial
A tutorial on setting up Dokku on your local machine via Vagrant and on AWS EC2. Thanks to [this article](https://medium.com/@alfeto/dokku-on-vagrant-and-aws-with-postgres-8a591bb48f51) for teaching me how to do this. 

## Installation
1. Clone the [Dokku repo](https://github.com/dokku/dokku) to your local machine  
`git clone git@github.com:dokku/dokku.git`

2. Install [Vagrant](https://docs.vagrantup.com) (I suggest installing via [brew cask](http://caskroom.io/))  
`brew cask install vagrant`

3. Install [VirtualBox](https://www.virtualbox.org) in order to set up Vagrant  
`brew cask install virtualbox`

4. (Optional) I would also install [Vagrant Manager](http://vagrantmanager.com) to manage your Vagrant machines  
`brew cask install vagrant-manager` 

## Set up project for Dokku
For this tutorial, I'm going to use an Express app as an example. You can fork the example app [here.](https://github.com/kevinnguy/express-example)

## Set up Dokku on your local Vagrant machine
1. Create the Vagrant virtual machine by changing directory to your local dokku repo  
`cd /path/to/local/dokku`

2. Create a Vagrant virtual machine with Dokku!  
`vagrant up`

Once Vagrant is done creating a virtual machine, access [10.0.0.2](10.0.0.2)

## Finish setting up Dokku on your local Vagrant machine
1. Access [10.0.0.2](10.0.0.2) on your browser.
