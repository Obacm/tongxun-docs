# 拒绝取消任务

拒绝取消的任务的消息

## 请求地址

> `task/[id]/cancel/refuse`

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
        "title": "碧云天拒绝任务取消申请",
        "user_id": 2
    }
}
```