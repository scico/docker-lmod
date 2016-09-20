lmod:centos7
============

A docker container with TACCs environmental modules system Lmod.   


The [Lmod](https://www.tacc.utexas.edu/research-development/tacc-projects/lmod) modules environment for management of MODULEPATH in a CentOS 7 image. 

To run a centos 7 container with Lmod 

```
$ docker run -ti docker.io/scico/easylmod bash
```

The image is, however, a base image and to be used to create a:

  1. package repo from Easybuild applications  
  2. docker image EasyBuild app registry 
