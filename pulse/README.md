# Dockerfile for running pulse secure VPN Client

```docker run -ti --rm -e DISPLAY=$DISPLAY  -e LD_LIBRARY_PATH=/usr/local/pulse --net host --privileged  -v /tmp/.X11-unix:/tmp/.X11-unix pulse bash```

once inside the container:

```/usr/local/pulse/pulseUi```

might crash for the first time
