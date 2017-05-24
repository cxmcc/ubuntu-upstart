# ubuntu-upstart

Latest docker image for `ubuntu-upstart`

### Description

This is the ubuntu 16.04 version of [ubuntu-upstart](https://hub.docker.com/_/ubuntu-upstart/]

In case you still need to use upstart in 16.04 in docker for whatever reason.

### Run the image

```sh
docker run \
    --cap-add=SYS_PTRACE \
    cxmcc/ubuntu-upstart:16.04
```

If this still does not work, try using `--privileged` flag or look into your apparmor logs.
