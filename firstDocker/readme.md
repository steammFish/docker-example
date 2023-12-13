## 初次探索docker

1. 创建并运行docker（官方：nginx）
docker run -it --rm -d -p 8080:80 --name website nginx

2. 查看docker中的服务
docker top website  

## 编译并运行docker

1. 编译docker镜像，（镜像名为 webserver）
docker build -t webserver .

2. 运行编译的docker镜像，（容器 web,镜像 webserver）
docker run -it --rm -d -p 8080:80 --name web webserver 

3. 查看nginx进程
 ps -C nginx -f

4. 重启 nginx
 nginx -s reload

5. 默认文件路径：
配置：`/etc/nginx/nginx.conf`,
     `/etc/nginx/conf.d/default.conf`
日志：`/var/log/nginx/`
网页：`/usr/share/nginx/html/`

## nginx with dns

docker-compose build


