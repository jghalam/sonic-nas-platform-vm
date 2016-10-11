SONiC NAS platform VM
=====================

VM (virtual-machine) platform specific utilities for the SONiC project

Description
-----------

This repo contains VM platform specific files and implementation for the Network abstraction service. There are confiugration files in this repo that defined port mapping etc.

Building
---------
Please see the instructions in the sonic-nas-manifest repo for more details on the common build tools.  [Sonic-nas-manifest](https://stash.force10networks.com/projects/SONIC/repos/sonic-nas-manifest/browse)

Build Requirements:
 - sonic-common-utils
 - sonic-object-library
 - sonic-base-model
 - sonic-logging
 - sonic-nas-ndi-api

Copy the debian files to the parent folder (default location of debian files) and then run the following command:
BUILD CMD: sonic_build --dpkg libsonic-logging1 libsonic-logging-dev libsonic-common1 libsonic-common-dev libsonic-object-library1 libsonic-object-library-dev libsonic-model1 libsonic-model-dev sonic-ndi-api-dev -- clean binary

(c) Dell 2016
