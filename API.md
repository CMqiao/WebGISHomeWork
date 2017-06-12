# API文档
## 用户管理
### 注册
#### Http请求
* URL: /map/user/register
* 方法：POST
* 参数：

参数名|类型|必选|说明
-|-|-|-
userName|String|true|用户名
password|String|true|密码
* 示例

```json
{
    "username":"admin",
    "password":"123456"
}
```

* Http响应

***成功***

```json
{
  "code": 0,
  "message": "注册成功",
  "data": {
    "id": 1,
    "userName": "admin"
  }
}
```

***失败***

```json
{
  "code": 1,
  "message": "注册失败",
  "data": null
}
```

### 登录
#### Http请求
* URL: /map/user/login
* 方法：POST
* 参数：

参数名|类型|必选|说明
-|-|-|-
userName|String|true|用户名
password|String|true|密码
* 示例

```json
{
    "username":"admin",
    "password":"123456"
}
```

* Http响应

***成功***

```json
{
  "code": 0,
  "message": "登录成功",
  "data": {
    "id": 1,
    "userName": "admin"
  }
}
```

***失败***

```json
{
  "code": 1,
  "message": "登录失败",
  "data": null
}
```