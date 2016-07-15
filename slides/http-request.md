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

因为我们的HTTP工作在应用层

所以可能会出现一种比较特殊的情况

类似HTTP 请求指定的主机地址和我们TCP 请求发送的地址不一样

这就给了我们抓取 HTTP 请求的机会



