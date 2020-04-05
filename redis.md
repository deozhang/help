#### docker拉取最新版的 Redis 镜像
```docker pull redis:latest```

#### 查看是否已成功安装了 redis镜像
```docker images```

#### 运行容器(--name后跟的是容器名)
```docker run -itd --name redis -p 6379:6379 redis```

#### 通过 redis-cli 连接测试使用 redis 服务
```docker exec -it redis /bin/bash```
```redis-cli```
 
#### 设置密码
```config set requirepass "123"```

#### 通过密码登录
```redis-cli -a 123```

#### 查询密码是否设置成功
```config set requirepass "123"```