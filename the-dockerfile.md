# The Dockerfile

## Your first Dockerfile

```
FROM alpine:3.7
```

Now, let's build and tag our first image

```
$ docker build -t first .
Sending build context to Docker daemon  2.048kB
Step 1/1 : FROM alpine:3.7
3.7: Pulling from library/alpine
2fdfe1cd78c2: Pull complete
Digest: sha256:ccba511b1d6b5f1d83825a94f9d5b05528db456d9cf14a1ea1db892c939cda64
Status: Downloaded newer image for alpine:3.7
 ---> e21c333399e0
Successfully built e21c333399e0
Successfully tagged first:latest
```

We can now use our image

```
$ docker run first
/ #
```

## The RUN and PWD commands



