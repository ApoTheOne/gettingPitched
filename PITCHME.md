# Docker containers and networking.
---
- Creating images
- Running containers |
- Networking |
---
# - Networking

'''
docker network create testnw
docker create --name my-nginx --network testnw -p 8080:80 nginx:latest
docker network connect testnw my-nginx
+++
# THANK YOU

