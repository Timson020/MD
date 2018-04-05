[TOC]

# 项目名

# 范例
- 请求地址-范例
	- 1xx.1xx.xx.xx:8081/name/1.0/user/xxx
- 请求内容-范例
```
{
	userId: 'xxx',
	passWord: 'xxx',
	token: 'xxx',
}
```
- 返回内容-范例

>返回内容格式是规定的

```
{
	code: 200, // number 只要没有逻辑错误都要返回200 其他状态由后端开发人员定义 （建议参照 网络状态status 定义）
	data: {}, // object || array || number || string 原本应该返回数组的，哪怕数组长度为0 都要返回数组类型 以此类推
	msg: '' // string 只能是字符串类型
}
```

# 服务器 --- xxx.com
> 1xx.1xx.xx.xx
8081

# 前缀-infix
/name/1.0/

# 用户相关 --- user/

## 用户登录d
> login
> post

	// request
	{
		user_id: 'xxx',
		password: 'xxx',
	}
	
	// response
	{
		code: 200,
		data: {},
		msg: ''
	}

