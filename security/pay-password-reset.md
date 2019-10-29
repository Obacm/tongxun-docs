# 支付密码重置

用户重新设置支付密码

## 请求地址

> `security/pay_password/reset`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `old_pay_password` `string` 原来的支付密码
> - `pay_password` `string` 支付密码
> - `pay_password_confirmation` `string` 支付密码确认

## 响应示例

```json
{
    "ok": 1
}
```

## 异常示例

> - `支付密码必须是六位数字`
> - `尚未设置支付密码`
> - `支付密码两次输入不一致`

```json
{
    "errno": 10006,
    "msg": "支付密码有误",
    "ok": 0
}
```
