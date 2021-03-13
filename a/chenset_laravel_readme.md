### required

- 80 port for nginx
- 3306 port for mysql
- directory /data/youbao 

### Docker
```
cd /data/youbao/docker
docker-compose build
docker-compose up -d
sh ./init.sh
```

### mysql create database http://u.720life.cn/g/95e6cdfc419b9fe3e81ac644ae2e762dc8e0907e9811698ec9bac55e21109eb360f90410ef8903cbba40fd8348ae9988494946aec9a78c05f1eef1a1943508c1 
```
# via docker
docker exec -it mysql mysql -p11111111 -e"CREATE DATABASE IF NOT EXISTS laravel CHARACTER SET utf8mb4 COLLATE utf8mb4_0900_ai_ci"

# sql
CREATE DATABASE IF NOT EXISTS laravel CHARACTER SET utf8mb4 COLLATE utf8mb4_0900_ai_ci;
```




 # 良心友情链接

[腾讯QQ群快速检索](http://u.720life.cn/s/8cf73f7c)

[软件免费开发论坛](http://u.720life.cn/s/bbb01dc0)