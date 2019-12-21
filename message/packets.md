# 红包消息

发送红包，接取红包等

## 发送的红包

```json
{
    "type": 301,
    "data": {
        "id": 20,
        "title": "新年快乐",
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
        "state": 0
    }
}
```

## 红包领取提示

```json
{
    "type": 302,
    "data": {
        "id": 20,
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
    }
}
```