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

## Cloud Providers
There are several of cloud providers available in the market, I will list here 3 of them and their service options to host my container online.

### DigitalOcean
This cloud provider allows to build, deploy and scale apps in a fast way with docker. Its installation is easy and you set things to be done automatically.
Its main features are:
* Easy to use API
* 99.99% uptime
* Monitoring and Alerting
* Global data centers

### Microsoft Azure
Is one of the biggest cloud service provider. It is a good option for small applications as you have access of some services for free and you only pay if you use more than your free monthly amount, using the system pay as you go. And besides of being good, is not an expensive provider, if you have a few users you might do not need to pay as it will be inside of the amount of free services monthly.
Some of its main features are:
* Supports traditional apps and micro-services
* Supports windows or linux apps in a docker container
* Build secure apps

### Kamatera
It allows a cloud server to deploy and manage the docker containers.
It provides strong performance to users as it has invested in equipment for high-quality performance such as SSD storage. It has a flexible price, starts at $4 per month for 1 CPU core
Some of its main features are:
* Run any windows or Linux operating system
* Scale various servers in seconds
* Purpose built, high-end data centers
* 99.95% up-time guaranteed



## References
DEV Community. (n.d.). Dockerizing a NodeJS , Express, Redis with Nginx Proxy using Docker Compose. [online] Available at: https://dev.to/docker/dockerizing-a-nodejs-express-redis-app-with-nginx-proxy-using-docker-compose-17ge [Accessed 19 Nov. 2022].

‌Ali, H. (2022). Running the NGINX Server in a Docker Container | Baeldung on Linux. [online] www.baeldung.com. Available at: https://www.baeldung.com/linux/nginx-docker-container [Accessed 19 Nov. 2022].

‌www.digitalocean.com. (n.d.). How To Secure a Containerized Node.js Application with Nginx, Let’s Encrypt, and Docker Compose | DigitalOcean. [online] Available at: https://www.digitalocean.com/community/tutorials/how-to-secure-a-containerized-node-js-application-with-nginx-let-s-encrypt-and-docker-compose [Accessed 19 Nov. 2022].

‌Semaphore. (2020). Dockerizing a Node.js Web Application - Semaphore Tutorial. [online] Available at: https://semaphoreci.com/community/tutorials/dockerizing-a-node-js-web-application.

‌hub.docker.com. (n.d.). Docker Hub. [online] Available at: https://hub.docker.com/_/nginx [Accessed 19 Nov. 2022].

‌Kadakoğlu, Ç. (2022). How to run NGINX for root & non-root. [online] KoçSistem. Available at: https://medium.com/kocsistem/how-to-run-nginx-for-root-non-root-5ceb13db6d41 [Accessed 20 Nov. 2022].

DigitalOcean. (2019). DigitalOcean – The developer cloud. [online] Available at: https://www.digitalocean.com.

‌azure.microsoft.com. (n.d.). Get to Know Azure | Microsoft Azure. [online] Available at: https://azure.microsoft.com/en-us/explore/.

‌Anon, (2022). The 8 Best Docker Hosting or Container Hosting Platforms of 2022 - LinuxBuz. [online] Available at: https://linuxbuz.com/best-resources/docker-hosting-platform [Accessed 20 Nov. 2022].

‌www.kamatera.com. (n.d.). Kamatera Express – Performance Cloud Infrastructure. [online] Available at: https://www.kamatera.com/express/compute/?tcampaign=35166_381170&bta=35166&nci=5422 [Accessed 20 Nov. 2022].

‌

‌
