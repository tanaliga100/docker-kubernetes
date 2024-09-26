# L05-02

Open a command prompt/terminal or use built-in terminal in Code using the **Terminal/New Terminal** menu or the **Ctrl-Shift-`** shortcut (that's a backtick).

Type the following Docker commands:

## Displays system information

    docker info

## Displays the system’s version

    docker version

## Log in to Docker Hub

    docker login

**INSIDE DOCKER**

## Pull and image to registry

    docker pull nginx

## Run Containers

    docker run nginx

## Detached mode

    docker run -D nginx

## Start containers

    docker start nginx

## Stop containers

    docker stop nginx

## Kill containers

    docker kill nginx

## List of running containers

    docker ps

## List of all the containers

    docker ps -a

## Get image info

    docker image inspect nginx
