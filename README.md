# Simple Notes App for TWS Community
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/LondheShubham153/django-notes-app.git
```

2. Create a Dockerfile for django-app

3. Create a docker volume and a docker bridge network for enabling comunication between docker containers
   
   `docker volume create mysql-data`
   `docker network create mynetwork -d bridge`

4. Create a docker-compose file 

5. Run the application from docker-compose.yml
   
   ```docker compose up -d
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
