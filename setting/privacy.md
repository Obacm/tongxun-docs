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

> - `mobile_enabled` 手机  `[0, 1]`
> - `qa_enabled` 问答  `[0, 1]`
> - `task_enabled` 任务  `[0, 1]`
> - `email_enabled` 邮箱  `[0, 1]`
> - `gender_enabled` 性别  `[0, 1]`
> - `address_enabled` 地址  `[0, 1]`

## 响应示例

```json
{
    "ok": 1
}
```