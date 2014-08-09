# pane

## Install MSI
msiexec /i A:\Example.msi
/a

- compat libraries
  - io / path
  - cookiecutter client

## Set PATH
- powershell
[Environment]::SetEnvironmentVariable("Path", "$env:Path;C:\Python27\;C:\Python27\Scripts\", "User")


older versions of Windows C:\AUTOEXEC.BAT 
Windows NT C:\AUTOEXEC.NT

PATH=%PATH%;C:\Python%PYVER%
- restart the system. 

[![Build Status](https://secure.travis-ci.org/michaeljoseph/pane.png)](http://travis-ci.org/michaeljoseph/pane)
[![Stories in Ready](https://badge.waffle.io/michaeljoseph/pane.png?label=ready)](https://waffle.io/michaeljoseph/pane) [![pypi version](https://badge.fury.io/py/pane.png)](http://badge.fury.io/py/pane)
[![# of downloads](https://pypip.in/d/pane/badge.png)](https://crate.io/packages/pane?version=latest)
[![code coverage](https://coveralls.io/repos/michaeljoseph/pane/badge.png?branch=master)](https://coveralls.io/r/michaeljoseph/pane?branch=master)

## Overview

Python Library Boilerplate contains all the boilerplate you need to create a Python package.

* features
* and stuff 

## Usage

Install `pane`:

    pip install pane

Then execute the sample cli:

   pane

## Documentation

[API Documentation](http://pane.rtfd.org)

## Testing

Install development requirements:

    pip install -r requirements.txt

Tests can then be run with:

    nosetests

Lint the project with:

    flake8 pane tests

## API documentation

Generate the documentation with:

    cd docs && PYTHONPATH=.. make singlehtml

To monitor changes to Python files and execute flake8 and nosetests
automatically, execute the following from the root project directory:

   tdaemon

- setuptools  extras
- platform deps
  - os.shell
brew install 
apt-get install
cinst 
- detect 


wget (New-Object System.Net.WebClient).DownloadFile("http://blog.commandlinekungfu.com","c:\downloadedfile.html")
- via http://blog.commandlinekungfu.com/2009/11/episode-70-tangled-web.html

@powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin

# Resources
https://docs.python.org/2/faq/windows.html
https://pip.pypa.io/en/latest/installing.html
http://arunrocks.com/guide-to-install-python-or-pip-on-windows/
https://docs.python.org/3.3/using/windows.html
http://docs.python-guide.org/en/latest/starting/install/win/
http://www.swaroopch.com/notes/python/#dos_prompt

http://technet.microsoft.com/en-us/library/cc759262(v=ws.10).aspx
