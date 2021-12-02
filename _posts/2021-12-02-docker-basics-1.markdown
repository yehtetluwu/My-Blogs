---
layout: post
title:  "Docker Basics - 1"
date:   2021-12-02 12:05:17 +0630
categories: jekyll update
---
# Part 1

## What is Docker? 
> Docker is an open-source containerization platform. It's also and open platform for developing and running softwares. Docker lets you seperate your applications from your infrastructure so that you can deliver softwares quickly. You can also control your infrastructures like you do to your applications with docker. Docker has an invironment where you can test/run your applications in an isolated place called containers.

## Contaners
> Containers are "standardized executable components combining application source code with the operating system (OS) libraries and dependencies required to run that code in any environment". You can install any dependencies and packages you need for your applciation and run it in a docker container. 

## Architecture and how it works
> When you run a docker commmand, the docker client contacts the docker daemon which basically takes in docker API requests. Let's say you want to create a container from a premade image from the registry. The docker daemon will look for the image you want from the registry and will make it for you. All you have to do is run a command from the docker client. REST API is used when docker client and daemon contact each other. 
![docker_archi](/assets/images/docker_archi.png "docker_archi")

## Pulling an image
> To create an image for your container, all you have to do is run `docker pull [OPTIONS] NAME[:TAG|@DIGEST]`. There are also few more options like `--disable-content-trust` that can be used together with the pull command.
Here is an example of pulling an image.
![docker_pull](/assets/images/docker_pull.png "docker_pull")

## Making your own image
> Sometimes you want to create an image where there is not only the OS for the image but also other dependicies, services or anything you want. Docker lets you customize your image so that you can set it up in a way where everything you need is ready when you create a container with that image. You need to write a dockerfile in order to do that. Then you have to run `docker build [OPTIONS] PATH | URL | -`
![dockerfile](/assets/images/dockerfile.png "dockerfile")

## Creating a container
> To create a container from the image you pull, you need to run `docker create [OPTIONS] IMAGE [COMMAND] [ARG...]`. There are also a [lists][lists] of options you can use when you create a container. Here is an example of creating a container from fedora together with the options `-i : Keep STDIN open even if not attached` and `-t : Allocate a pseudo-TTY`. 
![docker_create](/assets/images/docker_create.png "docker_create")
> To create a container from a dockerfile, you need to run `docker run [OPTIONS] IMAGE [COMMAND] [ARG...]` and it will not only create the container but also run everything that you specified in the dockerfile. 

### You can also check out [docker][docker] for more information on the official website.
![docker_logo](/assets/images/docker_logo.png "logo")


[lists]: https://docs.docker.com/engine/reference/commandline/create/
[docker]: https://docs.docker.com/