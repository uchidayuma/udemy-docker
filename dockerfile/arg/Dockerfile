FROM ubuntu:20.04
RUN apt-get update -y && \
    apt-get install -y nginx
ARG APP_ENV="local"
#--bulid-argがない場合はlocalがセットされる
CMD ["nginx", "-g", "daemon off;"] 
