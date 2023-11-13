# Docker Commands

Some of the most commonly used docker commands are 

### `docker ps`

List containers

### `docker ps -a`

Show all containers (default shows just running)

### `docker run [image name]`

Run specific image

### `docker images`

Lists docker images on the host machine.

### `docker build`

Builds image from Dockerfile.


### `docker image rm [image name]`

Remove a specific image


### `docker image rm $(docker images -a -q)`

Remove all images
