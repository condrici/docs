# Docker

## Common Commands

- docker build
- docker run
- 
- docker volume
- 
- docker rm
- docker rmi
- docker stop
- docker pause
- 
- docker logs
- docker events
- docker version
- docker update
- docker top
- docker stats
-
- docker network
- docker network ls
- docker network connect <net nme>
- docker network inspect <net nme>
- 
- docker-compose
- docker-compose up
- docker-compose up -d (run in bg)
- docker-compose up -d --no-deps --build <service_name> (build before starting container)
- docker-compose up -d --force-recreate (recreate container)
- docker-compose down
- docker-compose restart (does not affect changes in yaml)
-
- docker secret
- docker secret create
- docker secret inspect
- docker secret ls
- docker secret rm

- 
- docker image
- docker image ls
- docker image rm
- 
- docker exec
- docker exec <machine> <command>
- 
- docker stop $(docker ps -a -q) (stop all containers)
- docker rm $(docker ps -a -q) (remove all containers)
