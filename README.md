==========================
packer-templates
==========================
forked from: https://github.com/shiguredo/packer-templates

Packer templates for building base VM boxes.

Usage
=====

Installing Packer
-----------------

Download the latest packer from http://www.packer.io/downloads.html and unzip the appropriate directory.

If you're using Homebrew

::

    $ brew tap homebrew/binary
    $ brew install packer


Running Packer
--------------

::

    $ git clone https://github.com/shiguredo/packer-templates
    $ cd packer-templates
    $ packer build template.json


If you want to build only virtualbox.

::

    $ packer build -only=virtualbox-iso template.json


Parallel builds can be run on 0.6.0 or latest packer version.

::

    $ packer build -parallel=true template.json


Supported versions
------------------

These templates was tested using a packer 0.7.5 .

