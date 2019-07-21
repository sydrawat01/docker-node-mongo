# Docker Node MongoDB Example

> Simple example of a dockerized Node/Mongo app

## Quick Start

```bash
# Run in Docker
docker-compose up
# use -d flag to run in background

# Tear down
docker-compose down

# To be able to edit files, add volume to compose file
volumes: ['./:/usr/src/app']

# To re-build
docker-compose build
```
> To check the app, just go to ```localhost``` or ```locahost:80``` on the browser after the command ```docker-compose up```.

Check out the [repository](https://hub.docker.com/r/sydrawat/docker-node-mongo)!

I've made this following [Brad Traversey on YouTube](https://www.youtube.com/watch?v=hP77Rua1E0c).
