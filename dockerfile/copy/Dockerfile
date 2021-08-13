FROM ubuntu:20.04
RUN apt-get update -y && \
    apt-get install -y nginx
COPY index.html /var/www/html
CMD ["nginx", "-g", "daemon off;"] 
