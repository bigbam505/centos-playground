Centos Playground
==================


This repo is suppose to be an easy way to obtain a centos 7 node using vagrant and virtual box.  There are two dependencies you will need to install before this will work:

* [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
* [Vagrant](https://www.vagrantup.com/downloads.html)

Once you have installed these look below for how to get started

## Usage

You will need run the following in the root of this directory


```bash
# Download and create the VM with the following command
vagrant up --provider virtualbox

# ssh into the host with below
vagrant ssh

# Once you are done or if you break anything..... (its ok!)
vagrant destroy
```


## Other Links and Resources

Just some reading materials in case you want to know more of what is going on

* [Vagrant Documentation](https://docs.vagrantup.com/v2/getting-started/index.html)
