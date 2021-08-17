# simple-express

- Build Dockerfile
  `docker build . -t simple-express`

- Instantiate a container from image (-d is detached mode)
  `docker-compose up -d`
  Or not a docker-compose: `docker run -itd --name simple-express2 -p 8081:8080 -d simple-express:latest`

- Go inside the container
  `docker exec -it simple-express bash`
