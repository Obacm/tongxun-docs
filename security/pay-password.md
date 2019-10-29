# 支付密码设置

用户设置支付密码

## 请求地址

> `security/pay_password`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `pay_password` `string` 支付密码
> - `pay_password_confirmation` `string` 支付密码确认

## 响应示例

```json
{
    "ok": 1
}
```

## 异常示例

> - `已设置支付密码`
> - `支付密码两次输入不一致`

```json
{
    "errno": 20032,
    "msg": "已设置支付密码",
    "ok": 0
}
```
