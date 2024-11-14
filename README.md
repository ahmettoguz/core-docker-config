## 🚀🚀🚀 Dev Commands 🚀🚀🚀

```
docker compose -p core build
docker compose -p core up -d
docker compose -p core up -d --build
docker compose -p core down

docker compose -p core build my-sql
docker compose -p core up -d my-sql
docker compose -p core up --build -d my-sql
docker compose -p core down my-sql
docker start core-mysql-image-container
docker stop core-mysql-image-container
docker rm core-mysql-image-container
docker rmi core-mysql-image

docker compose -p core build php-myadmin
docker compose -p core up -d php-myadmin
docker compose -p core up --build -d php-myadmin
docker compose -p core down php-myadmin
docker start core-core-phpmyadmin-container-container
docker stop core-core-phpmyadmin-container-container
docker rm core-core-phpmyadmin-container-container
docker rmi core-phpmyadmin-image

docker compose -p core build database-initializer-mysql
docker compose -p core up -d database-initializer-mysql
docker compose -p core up --build -d database-initializer-mysql
docker compose -p core down database-initializer-mysql
docker start core-database-initializer-alpine-mysql-client-container
docker stop core-database-initializer-alpine-mysql-client-container
docker rm core-database-initializer-alpine-mysql-client-container
docker rmi core-database-initializer-image

docker exec -it core-database-initializer-alpine-mysql-client-container /bin/sh
docker inspect core-database-initializer-alpine-mysql-client-container
docker logs core-database-initializer-alpine-mysql-client-container
cls
```