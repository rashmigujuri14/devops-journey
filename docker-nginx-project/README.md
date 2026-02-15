# Docker Nginx Website Deployment

## Overview
Deployed a custom static website using Docker and Nginx inside a Virtual Machine.

## Run Command
sudo docker run -d -p 9090:80 -v $(pwd):/usr/share/nginx/html nginx

## Access
http://172.16.16.101:9090

## Concepts Covered
- Docker container
- Port mapping
- Volume mapping
- Port conflict resolution
- VM networking troubleshooting
