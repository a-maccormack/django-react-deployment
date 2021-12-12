# Django React Docker Boilerplate #

A simple Django, React, Docker deployment Boilerplate. Works locally. Endpoints must be adjusted to suit specific production environment.

## Technologies used:

Technology Type    |Name
-------------------|-----
 Backend           | Django
 Frontend          | ReactJS
 Database          | PostgreSQL
 Container         | Docker
 WebServer         | Nginx
 Proxy             | CloudFlare
 
 ## Prerequisites
 ```
 docker-compose 1.29.2
 ```
 
 ## Steps:
 
 1) Clone repository:  ```git clone https://github.com/a-maccormack/django-react-deployment.git```
 
 2) Add all Cloudflare SSL certificates accordingly. ```nginx/ssl-certificates/```
 
 3) Uncomment and modify lines: 9,10,19,20,21 in ```nginx/nginx-proxy.conf``` to include your newly added SSL certificates.
 
 4) Build Project: ```docker-compose build```
 
 5) Compose Up: ```docker-compose up```
 
 6) You're done!
