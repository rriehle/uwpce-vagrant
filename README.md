# uwpce-vagrant
A vagrant build for a python development environment

![Image](screenshot.png?raw=true)

One of the challenges we face as developers on a team or as students in a classroom setting is getting everyone quickly up and running with a full fledged, feature rich, functional and consistent, homogenous Python development environment.  Vagrant allows us to quickly build a virtual machine with everything we'll need.

The Vagrantfile in this repo builds an Ubuntu Linux virtual machine.  It pre-installs the latest versions of programming editors and IDEs (Integrated Development Environments) and requires about 30 minutes to build on a fast network.  It should work on Linux, OS X or Windows so that by the end of the installation you will have an Ubuntu Linux virtual machine running on top of your host operating system, be it OS X, Windows, or another instance of Linux.

Pre-installed Software
----------------------

*  [Python3](https://docs.python.org/3/)
*  [Atom](https://atom.io)
*  [bpython](http://bpython-interpreter.org)
*  [Emacs](https://www.gnu.org/software/emacs/)
*  [IDLE](https://docs.python.org/3/library/idle.html)
*  [IPython](http://ipython.org) and [Jupyter](http://jupyter.org)
*  [PyCharm](https://www.jetbrains.com/pycharm/)
*  [Sublime Text](http://www.sublimetext.com)
*  [Vim](http://www.vim.org)
*  [Virtualenv](https://pypi.python.org/pypi/virtualenv)
*  [Vritualenvwrapper](https://pypi.python.org/pypi/virtualenvwrapper)
*  ...and more

Prerequisites
-------------

1.  Install Virtual Box for your host operating system

    https://www.virtualbox.org

2.  Install Vagrant for your host operating system

    https://www.vagrantup.com

Installation Steps
------------------

1.  Attach your computer to a fast network, attach your laptop to a power supply to prevent it from going to sleep, provide for up to four hours for the 'vagrant up' command to do its work.  When wired onto a fast home network 'vagrant up' might take only twenty minutes.

2a.  First option: clone this repo, change into the directory and start the vagrant build:

    ```
    $ git clone https://github.com/rriehle/uwpce-vagrant.git
    $ cd uwpce-vagrant
    $ vagrant up
    ```

2b.  Second option: if you don't have git installed on your local/target machine, download these files as a zip archive using the Clone or download button, unzip the files, change into the directory with the Vagrant file, and start the vagrant build.

<div class="file-navigation in-mid-page">

    <div class="select-menu get-repo-select-menu js-menu-container float-right select-menu-modal-right">
  <button class="btn btn-sm btn-primary select-menu-button js-menu-target"
    title="Clone or download this repository"
    type="button" aria-label="Clone or download this repository" tabindex="0" aria-haspopup="true">
    <span>Clone or download</span>
  </button>

  <div class="select-menu-modal-holder dropdown-menu-content js-menu-content" aria-hidden="true">
    <div class="get-repo-modal dropdown-menu dropdown-menu-sw pb-0 js-toggler-container on">
      <div class="clone-options https-clone-options">
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=push" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="hYd2rcUMxURGEOssCCO936DZkAXXR+wUUnvxKlg7Z06NCJQg7c53fsbK2QSlgKMi1IIaGfG9/NXfBpQmyS9b3w==" /></div><button class="btn-link btn-change-protocol js-toggler-target float-right" type="submit">Use SSH</button></form>

        <h4 class="mb-1">
          Clone with HTTPS
          <a class="muted-link" href="https://help.github.com/articles/which-remote-url-should-i-use" target="_blank">
            <svg aria-hidden="true" class="octicon octicon-question" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M6 10h2v2H6v-2zm4-3.5C10 8.64 8 9 8 9H6c0-.55.45-1 1-1h.5c.28 0 .5-.22.5-.5v-1c0-.28-.22-.5-.5-.5h-1c-.28 0-.5.22-.5.5V7H4c0-1.5 1.5-3 3-3s3 1 3 2.5zM7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7z"/></svg>
          </a>
        </h4>
        <p class="mb-2 get-repo-decription-text">
          Use Git or checkout with SVN using the web URL.
        </p>

        <div class="input-group js-zeroclipboard-container">
  <input type="text" class="form-control input-monospace input-sm js-zeroclipboard-target js-url-field" value="https://github.com/rriehle/uwpce-vagrant.git" aria-label="Clone this repository at https://github.com/rriehle/uwpce-vagrant.git" readonly>
  <div class="input-group-button">
    <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><svg aria-hidden="true" class="octicon octicon-clippy" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M2 13h4v1H2v-1zm5-6H2v1h5V7zm2 3V8l-3 3 3 3v-2h5v-2H9zM4.5 9H2v1h2.5V9zM2 12h2.5v-1H2v1zm9 1h1v2c-.02.28-.11.52-.3.7-.19.18-.42.28-.7.3H1c-.55 0-1-.45-1-1V4c0-.55.45-1 1-1h3c0-1.11.89-2 2-2 1.11 0 2 .89 2 2h3c.55 0 1 .45 1 1v5h-1V6H1v9h10v-2zM2 5h8c0-.55-.45-1-1-1H8c-.55 0-1-.45-1-1s-.45-1-1-1-1 .45-1 1-.45 1-1 1H3c-.55 0-1 .45-1 1z"/></svg></button>
  </div>
</div>

<!-- ![Image](zip-download.png?raw=true) -->

    ```
    $ cd uwpce-vagrant
    #vagrant up
    ```

3.  Restart your new virtual computer and login:

    ```
    $ vagrant reload
    ```

    Username: vagrant<br>
    Password: vagrant

Usability Notes
---------------

Disable screen saver and power management within the virtual machine.  These issues are best left to the host computer.

![Image](screenshot-screensaver.png?raw=true)

Windows Issues
--------------

[Run Hyper-V and VirtualBox on the same machine](https://derekgusoff.wordpress.com/2012/09/05/run-hyper-v-and-virtualbox-on-the-same-machine/)  Tl;dr: You might need to disable Hyper-V when using VirtualBox.

[Can't download boxes on Windows 10.](https://github.com/mitchellh/vagrant/issues/6754)  Tl;dr: You might need to download Microsoft's .NET Redistributable Framework.
