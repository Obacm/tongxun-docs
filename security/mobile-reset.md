# 重置手机号

用户修改手机号码

## 请求地址

> `security/mobile/reset`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `mobile` `string` 手机号
> - `verify_code` `string` 短信验证码

## 响应示例

```json
{
    "ok": 1
}
```

## 异常示例

> - `短信验证码错误`

```json
{
    "msg": "短信验证码错误",
    "ok": 0
}
```
