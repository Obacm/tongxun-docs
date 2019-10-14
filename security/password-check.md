# 用户登陆密码检查

通知消息设置

## 请求地址

> `security/password/check`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `password` `string` 密码

## 响应示例

```json
{
    "ok": 1
}
```

## 异常示例

> - `密码有误`

```json
{
    "msg": "密码有误",
    "ok": 0
}
```

