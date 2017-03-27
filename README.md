# natbusa/jupyterhub-tensorflow-lab

Built from the `jupyter/tensorflow-notebook` base image.  
see: https://github.com/jupyter/docker-stacks/tree/master/tensorflow-notebook

This image contains a single user notebook server for use with [JupyterHub](https://github.com/jupyterhub/jupyterhub). 
It is a small extension on the jupyterhub/systemuser, setting the necessary parameters for running JupyterLab by default. 
For more info on how to combine JupyterHub running jupyter lab docker images, read https://github.com/natbusa/docker-sysuser-scipy-lab

## use this image
This image has been uploaded on docker hub as [natbusa/jupyterhub-tensorflow-lab](https://hub.docker.com/r/natbusa/jupyterhub-tensorflow-lab/)

## build your own image

Use the command: `docker build .` and modify the `c.DockerSpawner.container_image` in your jupyterhub configuration accordingly.


