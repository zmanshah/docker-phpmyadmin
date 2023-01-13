# docker-phpmyadmin

Latest phpMyAdmin (5.2.0) build using slim Debian 11 (bullseye).

# Build docker image & run using dockerfile 

docker build -t image-name .

docker run --name container-name -d -p 80:80 image-name

# Build docker image & run using dockerfile

docker-compose build

docker-compose up -d
