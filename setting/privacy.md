# 用户隐私设置

设置用户的个人隐私

## 请求地址

> `setting/privacy`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 请求参数

> - `mobile_enabled` `int` 手机  `[0, 1]`
> - `qa_enabled` `int` 问答  `[0, 1]`
> - `task_enabled` `int` 任务  `[0, 1]`
> - `email_enabled` `int` 邮箱  `[0, 1]`
> - `gender_enabled` `int` 性别  `[0, 1]`
> - `address_enabled` `int` 地址  `[0, 1]`

## 响应示例

```json
{
    "ok": 1
}
```