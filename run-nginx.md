# Run Nginx Container

## Pull the image
docker pull nginx

## Run the container
docker run -d --name mj-nginx -p 8080:80 nginx

## Check running containers
docker ps

## Stop the container
docker stop mj-nginx

## Remove the container
docker rm mj-nginx

## Remove the image
docker rmi nginx

## Explanation
- -d runs the container in detached mode
- --name my-nginx sets a name for the container
- -p 8080:80 maps port 8080 on the host to port 80 in the container
