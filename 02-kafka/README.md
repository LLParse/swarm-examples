Launch standalone zookeeper and kafka containers and link them. In context of Docker Swarm, an implicit dependency filter is created which tells the scheduler to co-locate the two containers on a host.

More info on swarm filters [here](https://docs.docker.com/swarm/scheduler/filter/).
