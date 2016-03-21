# Swarm scaling

The following template demonstrates Docker swarm scaling of a simple load-balanced python app with a redis backend.

## Instructions

Setup a Docker swarm

Set the VHOST environment variable
`export VHOST=192.168.99.101`

Launch the template in detached mode
`docker-compose up -d`

Scale web containers
`docker-compose scale web=3`

Verify connectivity
`curl $VHOST` should return something similar to this:
```

Hello World!
I have been seen 59 times.
My Host name is 3443e79962ee

```

## Credits

https://github.com/vegasbrianc/docker-compose-demo
