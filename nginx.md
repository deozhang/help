# docker拉取最新版的 Nginx 镜像
docker pull nginx:latest

# docker运行 nginx 容器
docker run --name nginx-test -p 8080:80 -d nginx
 