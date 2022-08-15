# nginx-demo
多项目使用子目录部署，nginx 配置遇到的问题

# 构建镜像启动容器
λ docker compose up

# 进入容器
docker exec -it demo-nginx-1 sh

# 更改 nginx.conf 后，在容器内重启 nginx
nginx -s reload 
