# 拒绝任务邀约

拒绝任务邀约

## 请求地址

> `task/[id]/invite/[id]/refuse`

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
    "type": 204,
    "body": {
        "title": "已拒绝您的邀约"
    }
}
```
