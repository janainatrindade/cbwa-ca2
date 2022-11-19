## CBWA - CA2
Docker Image using Alpine, Node.js and Nginx.

## Usage
1. Download the dockerfile
2. Execute Docker Desktop
3. If the image is hosted in your machine you should access the directory where the dockerfile is.
``` 
cd /Desktop/ImageDirectory 
```
4. Inside the directory build the image
``` 
docker build -t static-website . 
```
5. Run the image
``` 
docker run -it --rm -p 8080:8080 static-website 
```
6. And finally you can access in the browser
``` 
http://localhost:8080 
```

## References
DEV Community. (n.d.). Dockerizing a NodeJS , Express, Redis with Nginx Proxy using Docker Compose. [online] Available at: https://dev.to/docker/dockerizing-a-nodejs-express-redis-app-with-nginx-proxy-using-docker-compose-17ge [Accessed 19 Nov. 2022].

‌Ali, H. (2022). Running the NGINX Server in a Docker Container | Baeldung on Linux. [online] www.baeldung.com. Available at: https://www.baeldung.com/linux/nginx-docker-container [Accessed 19 Nov. 2022].

‌www.digitalocean.com. (n.d.). How To Secure a Containerized Node.js Application with Nginx, Let’s Encrypt, and Docker Compose | DigitalOcean. [online] Available at: https://www.digitalocean.com/community/tutorials/how-to-secure-a-containerized-node-js-application-with-nginx-let-s-encrypt-and-docker-compose [Accessed 19 Nov. 2022].

‌Semaphore. (2020). Dockerizing a Node.js Web Application - Semaphore Tutorial. [online] Available at: https://semaphoreci.com/community/tutorials/dockerizing-a-node-js-web-application.

‌hub.docker.com. (n.d.). Docker Hub. [online] Available at: https://hub.docker.com/_/nginx [Accessed 19 Nov. 2022].

‌
