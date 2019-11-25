# 交换手机

交换手机发起

## 请求地址

> `task/user/[id]/swap`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应示例

```json
{
    "ok": 1
}
```

## 云信消息

```json
{
    "type": 205,
    "body": {
        "title": "碧云天已向您发起了交换电话申请，请您确认是否同意",
        "user_id": 2
    }
}
```
