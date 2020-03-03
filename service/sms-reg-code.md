# 注册短信发送

用于注册账号发短信

## 请求地址

> `sms/reg_code`

## 请求类型

> `POST`

## 请求参数

#### Body

> - `mobile` `string` 手机号码

## 响应示例

```json
{
    "ok": 1
}
```

## 异常示例

> - `短信接口触发限制`
> - `手机已经存在`

```json
{
    "errno": 10009,
    "msg": "短信接口触发限制",
    "ok": 0
}
```