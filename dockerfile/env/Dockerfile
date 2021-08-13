FROM ubuntu:20.04
RUN apt-get update -y && \
    apt-get install -y nginx
ENV TESTENV="Uchida"
ENV APP_ENV="production"
#よく使うのが、locat,production
CMD ["nginx", "-g", "daemon off;"] 
