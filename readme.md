# Docker Commands

Some of the most commonly used docker commands are

### `sudo service docker start`

Start docker on WLS2

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


### `docker rm [image name]`

Remove a specific image

### `docker rm -f [image name]`

Force to remove a specific image


### `docker image rm $(docker images -a -q)`

Remove all images

### `docker -it`

-i keeps STDIN active to keep your process running
-t we can type on terminal
