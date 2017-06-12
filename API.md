# API文档
## 用户管理
### 注册
#### Http请求
* URL: map/user/login
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
    "password":"12345678"
}
```

* Http响应

```json
{
  "code": 0,
  "message": null,
  "errors": null,
  "data": {

    }
  }
}
```