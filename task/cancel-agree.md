# 同意取消任务

同意取消的任务的消息

## 请求地址

> `task/[id]/cancel/agree`

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
        "title": "碧云天同意任务取消申请",
        "user_id": 2
    }
}
```

## 云信任务通知

```json
{
    "type": 2073,
    "body": {
        "id": 17,
        "name": "任务订单反馈",
        "title": "上门修电脑",
        "user": {
            "id": 1,
            "tx_id": "f3d0d305f962",
            "name": "obacmss",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "description": "",
            "level": 0,
            "score": "2.0"
        },
        "remark": "您的任务已失效",
        "created_at": "2019-11-25 14:37:11"
    }
}
```