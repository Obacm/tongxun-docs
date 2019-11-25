# 拒绝交换手机

拒绝手机发起

## 请求地址

> `task/user/[id]/swap/refuse`

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
    "type": 206,
    "body": {
        "title": "已拒绝"
    }
}
```
