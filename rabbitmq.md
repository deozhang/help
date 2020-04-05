#### docker拉取RabbitMQ镜像
```docker pull rabbitmq:management```

#### 安装 RabbitMQ
```docker run --name rabbitmq -d -p 15672:15672 -p 5672:5672 rabbitmq:management```


#### 停止 RabbitMQ 容器
```docker stop rabbitmq```

#### 启动 RabbitMQ 容器
```docker start rabbitmq```

#### 重启 RabbitMQ 容器
```docker restart rabbitmq```

#### 查看 RabbitMQ 容器进程信息
```docker top rabbitmq```

#### 控制台信息
启动容器后，可以浏览器中访问[http://localhost:15672](http://localhost:15672)来查看控制台信息。
RabbitMQ默认的用户名：```guest```，密码：```guest```