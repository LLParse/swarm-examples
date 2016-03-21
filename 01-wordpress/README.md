A simple wordpress example which launches two linked containers onto a single host. 

Existing docker-compose templates may be launched onto docker swarms without any refactoring. The swarm manager extends the docker api and becomes `DOCKER_HOST` in order to acheieve this compatibility.
