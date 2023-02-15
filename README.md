# Intent
This is a reference project to quickly get a CI/CD pipeline up and running with TeamCity Professional (the on-premise/free version).

## History
Finding good documentation on how to properly setup a Docker-in-Docker configuration to run TeamCity - NodeJS Runners on a Macbook with Docker (installed via Docker Desktop) created a slight challenge and wasted too much time. This repository is to help others speed up their simple CI/CD implementation if using a similar machine.

## Start Here
#### If docker is installed with DockerDesktop, run the following to create a symlink
 - sudo ln -s /home/${user}/.docker/desktop/docker.sock /var/run/docker.sock
#### Go into Docker Desktop and find Resources > File Sharing
 - add the following: /agent_conf, data_dir/plugins, data_dir/system
## Usage
 - clone repository
 - cd to the project folder root
 - docker-compose up -d
