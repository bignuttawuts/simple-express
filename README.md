# simple-express

- Build Dockerfile
  `docker build . -t simple-express`

- Instantiate a container from image (-d is detached mode)
  `docker-compose up -d`
  Or not a docker-compose: `docker run -itd --name simple-express2 -p 8081:8080 -d simple-express:latest`

- Go inside the container
  `docker exec -it simple-express bash`

## To-do List

1. Initial node express with docker
2. Simple application node with MariaDB
3. Register with euraka
4. Call another service in among euraka
