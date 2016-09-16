docker-lmod-centos7
===================

A docker container with TACCs environmental modules system Lmod.   


The [Lmod](https://www.tacc.utexas.edu/research-development/tacc-projects/lmod) modules environment for management of MODUPLEPATH in a CentOS 7 image. 

To run a centos 7 image with Lmod 

```
$ docker run -ti docker.io/scico/lmod bash
```

The image is a base image to be used with 1) installed applications using Lmod or for 2) building further images depending on the presence of Lmod. 
