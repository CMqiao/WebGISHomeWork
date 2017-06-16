# WebGIS大作业后台API文档说明

## Introduction

* 本文档是 API 文档，符合 RESTFUL 风格，便于 web 前端调用接口。

* 测试地址：[http://www.qiaojizhen.cn](http://www.qiaojizhen.cn)

* 开发模式：[localhost:8080](http://localhost:8080)

### 请求

* 对于 POST 请求， 请求的主体必须是 JSON 格式，而且 HTTP header 的 Content-Type 需要设置为 **application/json**。
  ### 响应格式
* 对于所有的请求，响应格式都是一个 JSON 对象
* 一个 2XX 的状态码表示成功，格式如下：

```json
{
  "code":0,
  "message":"",
  "data": {
    "...":"...",
    "...":"...",
    "...":"..."
   }
}
```

### 注意事项

* 所有参数区分大小写，**JSON**格式

* [HTTP状态码](http://baike.baidu.com/link?url=H6rTlctgVHKJLgalwJjulT-4IsRjIoccbwjsX6p_p7NpORBVtDi8bf4zIewmSJE3SOuMku40KPL28_dqDsdLjq) 参考

# [文档地址](/chapter01.md)

_**Copyright \(C\) 2017 JiZhen Qiao**_

