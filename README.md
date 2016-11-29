mposplit
========
A small tool to convert a 3D MPO-file into two JPEG-files.

This is a mirrow of the original files from http://cstein.kings.cam.ac.uk/~chris/mposplit/index.html. It seems to be that the original server is down, but you can access the original page via archive.org (https://web.archive.org/web/20150927062911/http://cstein.kings.cam.ac.uk/~chris/mposplit/).

Tested with the following cameras
 * Fujifilm Real 3D W1
 * Fujifilm Real 3D W3
 * Ricoh CX5



Original mposplit.c: Copyright (C) 2009-2012, Christian Steinruecken

Usage
-----

```
$ mposplit file.mpo
```
  
Building
-------
**cmake**

```
$ git clone https://github.com/AlbrechtL/mposplit.git
$ cd mposplit/
mposplit$ mkdir build
mposplit$ cd build
mposplit/build$ cmake ../
mposplit/build$ make
```

**snapcraft**

```
$ git clone https://github.com/AlbrechtL/mposplit.git
$ cd mposplit/snap
mposplit/snap$ snapcraft
```
    
Installing
----------
1. Download the Ubuntu snap image from https://github.com/AlbrechtL/mposplit/releases/download/v0.1/mposplit_0.1_amd64.snap
2. Install the snap image

  ```
# sudo snap install --force-dangerous mposplit_0.1_amd64.snap
  ```
