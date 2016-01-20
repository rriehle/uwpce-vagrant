# uwpce-vagrant
A vagrant build for a python for a python development environment

One of the challenges we face in the program is getting everyone quickly up and running with a full fleged, feature rich, functional Python development envirionment.  Vagrant allows us to quickly build an virtual machine with everything we'll need.

The Vagrantfile in this repo will build an Ubuntu Linux virtual machine.  It should work on Linux, OS X or Windows.

Prerequisites
-------------

1.  Install Virtual Box for your host operating system
   https://www.virtualbox.org

2.  Install Vagrant for your host operating system
   https://www.vagrantup.com

Installation Steps
------------------

1.  Attach your computer to a fast network, attach your laptop to a power supply to prevent it from going to sleep, provide for up to 4 hours for the 'vagrant up' command to do its work.

2.  Clone this repo, change into the directory and start the vagrant build:

    ```
    $ git clone https://github.com/UWPCE-PythonCert/uwpce-vagrant.git
    $ cd uwpce-vagrant
    $ vagrant up
    ```

3.  Restart your new virtual computer and login:

    ```
    $ vagrant halt
    $ vagrant up
    $ vagrant ssh
    ```
