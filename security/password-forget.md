# 用户登陆忘记密码

用户根据手机修改登陆密码

## 请求地址

> `security/password/forget`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `mobile` `string` 手机号
> - `password` `string` 密码
> - `password_confirmation` `string` 密码确认

## 响应示例

```json
{
    "ok": 1
}
```
