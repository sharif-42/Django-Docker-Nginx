# Docker-Nginx
Basic NGINX and Docker project. 

## Add user credential to access the .../p1/ url/page
```shell
docker exec -it django-docker-nginx_nginx_1 sh -c "htpasswd -c /etc/pwd/.htpasswd <username>"
```