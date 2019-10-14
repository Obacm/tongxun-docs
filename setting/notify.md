# 用户通知设置

通知消息设置

## 请求地址

> `setting/notify`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 请求参数

> - `push_notify` `int` 推送  `[0, 1]`
> - `email_notify` `int` 邮箱  `[0, 1]`

## 响应示例

```json
{
    "ok": 1
}
```