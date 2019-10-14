# 短信验证

短信验证

## 请求地址

> `sms/verify`

## 请求类型

> `POST`

## 请求参数

#### Body

> - `mobile` `string` 手机号码
> - `verify_code` `string` 验证码

## 响应示例

```json
{
    "ko": 1
}
```

## 异常示例

> - `短信验证码错误`
> - `验证码 必须是 6 位的数字`

```json
{
    "msg": "短信验证码错误",
    "ok": 0
}
```