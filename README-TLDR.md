# Nginx Node React

1. Build server image from Dockerfile

`docker build -f Dockerfile -t server .`

2. Verify image created

`docker images`

3. Create new container

`docker run -it -p 4002:3000 server`

4. Visit browser

`http://localhost:4002/`

5. execute commands

`docker exec -it <container_name> npm -v`