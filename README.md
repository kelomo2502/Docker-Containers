# Docker-Containers

## Backfround

Docker containers are lightweight, portable, and executable units that encapsulate an application and its dependencies.

## Running containers

To run a container, you use the `docker run`  command followed by the name of the image you want to use.
sample
`docker run ubuntu`
To start the container
`docker start ubuntu`
Running container with specific environment variables
`docker run -e "MY_VARIABLE=my-value" ubuntu`
Running container on the background
`docker run -d ubuntu`

## Container life cycle

Containers have a lifecycle that includes creating, starting, stopping, and restarting. Once a container is created, it can be started and stopped multiple times.
`docker start container_name`
`docker stop container_name`
`docker restart container_name`
Removing a container
`docker rm container_name`

 