# docker-phpmyadmin

Latest phpMyAdmin build on slim debian OS
- Debian 11 (bullseye).
- phpMyAdmin 5.2.0
- PHP 8.0.27


# Build docker image & run using dockerfile 

docker build -t image-name .

docker run --name container-name -d -p 80:80 image-name

# Build docker image & run using docker-compose

docker-compose up -d

![image](https://user-images.githubusercontent.com/120363414/212216395-bf187837-f133-4b4a-bb66-c3db6032e589.png)

![image](https://user-images.githubusercontent.com/120363414/212216486-cf8693c7-926f-4337-87cf-efe23ca9976c.png)
