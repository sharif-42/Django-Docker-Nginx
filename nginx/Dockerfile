FROM nginx:latest

# COPY ./html /usr/share/nginx/html
RUN apt-get update

# To use basic http authentiaction
RUN apt-get install --no-install-recommends -y apache2-utils

RUN mkdir -p /home/app/staticfiles
RUN mkdir -p /etc/pwd
