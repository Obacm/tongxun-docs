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
        "user": {
            "id": 1,
            "tx_id": "f3d0d305f962",
            "accid": "yx_1",
            "name": "athena",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "5.0"
        },
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
        "task": {
            "id": 10,
            "title": "君不见"
        },
        "inviter": {
            "id": 1,
            "tx_id": "f3d0d305f962",
            "accid": "yx_1",
            "name": "athena",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "5.0"
        },
        "invitee": {
            "id": 2,
            "tx_id": "f3d0d305f962",
            "accid": "yx_2",
            "name": "obacm",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "5.0"
        }
    }
}
```

## 任务邀约同意

```json
{
    "type": 203,
    "data": {
        "inviter": {
            "id": 1,
            "tx_id": "f3d0d305f962",
            "accid": "yx_1",
            "name": "athena",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "5.0"
        },
        "invitee": {
            "id": 2,
            "tx_id": "f3d0d305f962",
            "accid": "yx_2",
            "name": "obacm",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "5.0"
        },
        "state": 1
    }
}
```

## 任务邀约拒绝

```json
{
    "type": 204,
    "data": {
        "inviter": {
            "id": 1,
            "tx_id": "f3d0d305f962",
            "accid": "yx_1",
            "name": "athena",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "5.0"
        },
        "invitee": {
            "id": 2,
            "tx_id": "f3d0d305f962",
            "accid": "yx_2",
            "name": "obacm",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "5.0"
        },
        "state": 0
    }
}
```

## 交换手机申请

```json
{
    "type": 205,
    "data": {
        "sender": {
            "id": 1,
            "tx_id": "f3d0d305f962",
            "accid": "yx_1",
            "name": "athena",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "5.0"
        },
        "swaper": {
            "id": 2,
            "tx_id": "f3d0d305f962",
            "accid": "yx_2",
            "name": "obacm",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "5.0"
        }
    }
}
```

## 交换手机申请拒绝

```json
{
    "type": 2052,
    "data": {
        "sender": {
            "id": 1,
            "tx_id": "f3d0d305f962",
            "accid": "yx_1",
            "name": "athena",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "5.0"
        },
        "swaper": {
            "id": 2,
            "tx_id": "f3d0d305f962",
            "accid": "yx_2",
            "name": "obacm",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "5.0"
        }
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