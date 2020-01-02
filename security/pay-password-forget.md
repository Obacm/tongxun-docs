# 忘记支付密码

用户根据注册的手机号修改支密码

## 请求地址

> `security/pay_password/forget`

## 请求类型

> `POST`

## 请求参数

#### Body

> - `verify_code` `string` 短信验证码
> - `pay_password` `string` 新的支付密码
> - `pay_password_confirmation` `string` 新的支付密码确认

## 响应示例

```json
{
    "ok": 1
}
```
