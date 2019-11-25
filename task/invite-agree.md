# 同意任务邀约

同意任务邀约

## 请求地址

> `task/[id]/invite/[id]/agree`

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
    "type": 203,
    "body": {
        "title": "已接受您的邀约"
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
        "user": "碧云天",
        "applier": "黄叶地",
        "remark": "对方已同意您的任务邀接",
        "applied_at": "2019-11-25 14:37:11"
    }
}
```

```json
{
    "type": 2073,
    "body": {
        "id": 17,
        "name": "任务订单反馈",
        "title": "上门修电脑",
        "user": "碧云天",
        "applier": "黄叶地",
        "remark": "您已同意对方的任务邀接",
        "applied_at": "2019-11-25 14:37:11"
    }
}
```