## 安装GCC 编译器

```c
	yum install gcc -y
```



## 进入Redis目录 ，执行编译

```c
cd  redis-5.0.4
    
make
```



## 进入src 目录，执行安装命令

```c
cd src && make install
```

​	

## 启动redis程序

```c
./redis-server  ../redis.conf
redis-cli
```

​	

## 修改redis.conf配置文件

```c
bind 0.0.0.0   ##允许任何地址访问 redis
daemonize yes   ##以后台进程redis    
protected-mode no  ## 关闭保护功能
requirepass root   ##  设置访问密码
```



## 开启防火墙端口



