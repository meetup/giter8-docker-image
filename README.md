# giter8 docker image

A simple containerization of [giter8](https://github.com/n8han/giter8). 

To use it:
```
docker run -v $PWD:/g8out meetup/g8 unfiltered/unfiltered.g8 --name=my-new-website
```

This will take generate a new `my-new-website` project based on the [`unfiltered/unfiltered.g8`](https://github.com/unfiltered/unfiltered.g8) template and place it in `my-new-website` under the current directory.

Or you can set the project properties interactivelly:
```
> docker run -v $PWD:/g8out -it meetup/g8 unfiltered/unfiltered.g8

This template generates an Unfiltered project

name [My Web Project]: my-new-website
version [0.1.0-SNAPSHOT]:
scala_version [2.12.4]:
sbt_version [1.1.0]:
unfiltered_version [0.9.1]:

Template applied in /g8out/./my-new-website
```
