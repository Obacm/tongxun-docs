# 用户登陆密码重置

用户修改登陆密码

## 请求地址

> `security/password/reset`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `old_password` `string` 旧密码
> - `password` `string` 密码
> - `password_confirmation` `string` 密码确认

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

```json
{
    "msg": "密码和旧密码必须不同",
    "ok": 0
}
```
