##  http Request

```
GET / HTTP/1.1
Accept: */*
Accept-Encoding: gzip, deflate
Connection: keep-alive
Host: baidu.com
User-Agent: HTTPie/0.9.3
```

note:

这是一个简单的HTTP请求的例子

我们知道即使创建一个 TCP 连接，我们也无法直接与
远程主机通信，必须通过各个路由器帮我们传递信息

因为我们工作在应用层

所以可能会出现一种比较特殊的情况

应用层的数据直接

我们可以看到里面只指定了远程主机的域名



