# 任务消息

包括任务邀约，任务分享，任务邀接等

## 任务沟通

```json
{
    "type": 201,
    "data": {
        "id": 20,
        "title": "电脑开不开机，黑屏",
        "hire_amount": "30.00",
        "fee_amount": "20.00",
        "description": "电脑开不开机，黑屏",
        "applier": {
            "id": 2,
            "tx_id": "f3d0d305f962",
            "accid": "yx_2",
            "name": "obacm",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "5.0"
        },
        "has_fee_amount": true,
        "created_at": "2019-11-25 14:37:11"
    }
}
```

## 任务邀约

```json
{
    "type": 202,
    "data": {
        "id": 10,
        "task_id": 20,
        "title": "任务申请",
        "content": "碧云天已向您发起了任务邀约申请，请您确认是否接受该申请。"
    }
}
```

## 任务邀约同意

```json
{
    "type": 203,
    "data": {
        "title": "已接受您的邀约"
    }
}
```

## 任务邀约拒绝

```json
{
    "type": 204,
    "data": {
        "title": "已拒绝您的邀约"
    }
}
```

## 交换手机申请

```json
{
    "type": 205,
    "data": {
        "title": "碧云天已向您发起了交换电话申请，请您确认是否同意。"
    }
}
```

## 交换手机申请拒绝

```json
{
    "type": 2052,
    "data": {
        "title": "已拒绝"
    }
}
```

## 任务分享

```json
{
    "type": 208,
    "data": {
        "id": 20,
        "title": "电脑开不开机，黑屏",
        "hire_amount": "30.00",
        "fee_amount": "20.00",
        "description": "电脑开不开机，黑屏",
        "user": {
            "id": 2,
            "tx_id": "f3d0d305f962",
            "accid": "yx_2",
            "name": "obacm",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "5.0"
        },
        "has_fee_amount": true,
        "created_at": "2019-11-25 14:37:11"
    }
}
```