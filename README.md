# overshadow

## Introduction

This is a Python based project to create a simple subsystem to install linux packages and their dependencies in user directories. It is meant to be used for PC's where sudo access is not available

This is based over `apt -download` and `dpkg -x` which downloads the packages in user space and unpacks them.
The paths need to be added to `.bashrc` so as to allow use over the commandline.

NOTE: This project is still in infancy, install and use at your own risk.

## Installation

Currently you have to use the project through the git source code. Work is being done on pushing this to PyPI.
