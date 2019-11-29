# overshadow

## Introduction

This is a Python based project to create a simple subsystem to install linux packages and their dependencies in user directories. It is meant to be used for PC's where sudo access is not available

This is based over `apt download` and `dpkg -x` which downloads the packages in user space and unpacks them.
The paths need to be added to `.bashrc` so as to allow use over the commandline.

NOTE: This project is still in infancy, install and use at your own risk.

## Installation

Currently you have to use the project through the git source code. Work is being done on pushing this to PyPI.


## Todo

- [ ] Where's the Source? `Python based Code on the way ASAP`
- [ ] My stuff says it can't find some thing it needs `Dependencies` `apt-cache depends <package name>`
- [ ] The package needs some folders that are explicitly present in a directory [Read Here](https://serverfault.com/questions/135599/ubuntu-can-non-root-user-run-process-in-chroot-jail)



 
