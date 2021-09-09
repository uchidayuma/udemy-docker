## このリポジトリについて

このリポジトリはUdemyで販売している「駆け出しエンジニアのためのDocker入門のソースコードリポジトリです。

購入がまだの方は[Udemy](https://www.udemy.com/course/docker-startup)からご購入ください。

[リポジトリURL](https://github.com/uchidayuma/udemy-docker.git)

##DockerPlayGround

[https://www.docker.com/play-with-docker](https://www.docker.com/play-with-docker)

### docker-composeインストールコマンド

```
curl -L https://github.com/docker/compose/releases/download/1.9.0/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
```

## Dockerfileのドキュメント

[ベストプラクティス](https://docs.docker.jp/engine/articles/dockerfile_best-practice.html)

[CMD](https://docs.docker.jp/engine/reference/builder.html#cmd)

## docker-compose

### 使用コマンド

- docker run -d -e MYSQL_ROOT_PASSWORD=somewordpress -e MYSQL_DATABASE=wordpress -e MYSQL_USER=wordpress -e MYSQL_PASSWORD=wordpress --name wordpress-db mariadb:10.4

## Laravel環境の構築

### 使用コマンド

- docker-compose run php composer create-project --prefer-dist laravel/laravel .
