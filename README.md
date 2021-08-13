

## Dockerfileのドキュメント
[ベストプラクティス](https://docs.docker.jp/engine/articles/dockerfile_best-practice.html)

[CMD](https://docs.docker.jp/engine/reference/builder.html#cmd)

## docker-compose
### 使用コマンド
docker run -d -e MYSQL_ROOT_PASSWORD=somewordpress -e MYSQL_DATABASE=wordpress -e MYSQL_USER=wordpress -e MYSQL_PASSWORD=wordpress --name wordpress-db mariadb:10.4
