# Docker Conda Jupyter

most basic docker image part of a full docker_gis stack. This docker image is based on Ubuntu 16.04 LTS and has Anaconda for Python and Jupyter as IDE. The Dockerfile exposes ports for Jupyter, PostgreSQL and VisDom. 

The docker image is tailored to cloud usage on Amazon EC2 instances, Google Compute engines etc.  

The docker image is stacked to minimize build time and dependencies. The full stack contains:

1. [docker_gis](https://github.com/rutgerhofste/docker_gis)
1. [docker_python_envs](https://github.com/rutgerhofste/docker_python_envs)
1. [docker_conda_jupyter](https://github.com/rutgerhofste/docker_conda_jupyter)

All images are hosted on [docker hub](https://hub.docker.com/u/rutgerhofste/)



