[TOC]

# 项目名

## 规范

- 接口定义: host.com/projectname/1/infix/api

- 使用RESTFUL-API
	- GET (获取操作)
	- POST (新增操作)
	- PATCH (修改信息操作)
	- PUT ()
	- DELETE (删除操作)

- header定义: { appVersion: '1.0.0', appToken: '' }

## 用户模块(user)

### 获取用户信息(getuserinfo)
>GET

```json
// Request
{}

// Responent
{
	"code": 200, // 200：成功, 404：查询失败
	"data": {}, // 
	"msg": "",
}
```

## 通用模块(common)

### 发送验证码(sendcode)
>POST

```json
// Request
{
	"mobile": "159xxxxxxxx"
}

// Responent
{
	"code": 200, // 200：成功, 404：发送失败
	"data": {}, // 
	"msg": "",
}
```