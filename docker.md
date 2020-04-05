#### Docker for Mac版本百度云链接
今天（2020/4/5）下载docker的Mac版本时，感觉对国内用户很不友好，网速很慢，一个700MB的安装包下载了整整一下午，所以，把这个Docker for Mac的安装包（版本：v19.03.8）上传到百度云，希望能够给后面的小伙伴节省一点时间吧。

```link
链接:https://pan.baidu.com/s/1oPk0HOPGfdpr9xXE8dHbAQ  
密码:6m9r
```

##### 启动docker

```sudo service docker start```

##### 停止docker

```sudo service docker stop```

##### 重启docker
```sudo service docker restart```

##### 列出镜像
```docker image ls```

##### 拉取镜像
```docker image pull library/hello-world```

##### 删除镜像
```docker image rm 镜像id/镜像ID```

##### 创建容器
```docker run [选项参数] 镜像名 [命令]```

##### 查看所有容器
```docker ps -a```

##### 停止一个已经在运行的容器
```docker container stop 容器名或容器id```

##### 启动一个已经停止的容器
```docker container start 容器名或容器id```

##### kill掉一个已经在运行的容器
```docker container kill 容器名或容器id```

##### 删除容器
```docker container rm 容器名或容器id```