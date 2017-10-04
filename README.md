# giter8 docker image

A simple containerization of [giter8](https://github.com/n8han/giter8). 

To use it:
```
docker run -v $PWD:/g8out meetup/g8 softprops/unfiltered.g8 --name=my-new-website
```

This will take generate a new `my-new-website` project based on the [`softprops/unfiltered.g8`](https://github.com/softprops/unfiltered.g8) template and place it in `my-new-website` under the current directory.
