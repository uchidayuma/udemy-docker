FROM mariadb:10.4
RUN apt-get update -y
COPY my.conf /etc/mysql/conf.d
COPY create-table.sql /docker-entrypoint-initdb.d
ENV MYSQL_USER=root
ENV MYSQL_DATABASE=docker
ENV MYSQL_ROOT_PASSWORD=root
