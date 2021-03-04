# dockerfiles

![publish_docs](https://github.com/macneib/dockerfiles/workflows/publish_docs/badge.svg)
![push_dockerfiles](https://github.com/macneib/dockerfiles/workflows/push_dockerfiles/badge.svg)

These are multi-stage docker images used for developing with [VSCode](https://code.visualstudio.com/).

This is a fork of the awesome [athackst dockerfiles repo](https://github.com/athackst/dockerfiles).

See [how I develop with vscode and docker](https://www.allisonthackston.com/articles/docker_development.html).

Instructions on how to duplicate my IDE:

* [vscode, docker, and ros2](https://www.allisonthackston.com/articles/vscode_docker_ros2.html)
* [vscode, docker, and github pages](https://www.allisonthackston.com/articles/vscode_docker_ros2.html)

## Quick start

Grab the docker image from [docker hub](https://hub.docker.com/u/macneib).  This repo provides the images in:

* [macneib/ros](https://hub.docker.com/r/macneib/ros)
* [macneib/ros2](https://hub.docker.com/r/macneib/ros2)
* [macneib/gazebo](https://hub.docker.com/r/macneib/gazebo)
* [atahckst/igntion](https://hub.docker.com/r/macneib/ignition)
* [macneib/github](https://hub.docker.com/r/macneib/github)

Then, set up a [vscode workspace](https://github.com/macneib/vscode_ros2_workspace).

## Build from source

Alternatively, you can build all the docker images directly from source.

```bash
./build.py all
```

Or just build one

```bash
./build.py foxy
```

To see help information and build options

```bash
./build.py --help
```


## Thank you

Many thanks to [athackst](https://www.allisonthackston.com) for providing this to the community!
