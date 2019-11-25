# 任务完成

评论已完成的任务

## 请求地址

> `task/[id]/complete`

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

## 云信任务通知

```json
{
    "type": 2071,
    "body": {
        "id": 17,
        "name": "任务已完成",
        "title": "上门修电脑",
        "user": "碧云天",
        "remark": "您的任务已被完成，请确认",
        "created_at": "2019-11-25 14:37:11"
    }
}
```
