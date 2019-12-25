# 流水详情

一条流水的详细信息

## 请求地址

> `wallet/water/[water]`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token


## 响应参数

>  `type` 账单类型 `1: 充值， 2: 提现，3: 任务支付，4: 红包支付，5: 红包退还，6: 红包进账，7: 任务赏金退还，8: 任务赏金进账`

## 响应示例

#### 发送的红包

```json
{
    "data": {
        "id": 209,
        "user": {
            "id": 20,
            "tx_id": "c4c2452c1214",
            "accid": "yx_20",
            "name": "obacmss",
            "avatar": "https://api.wtdoe.com/storage/default_avatars/pic_020.jpg",
            "bio": ""
        },
        "subject": "群聊（大江）",
        "actual_amount": "20.00",
        "waterable": {
            "id": 108,
            "user_id": 20,
            "order_no": "20191224133326758187",
            "trade_no": null,
            "data": {
                "type": 1,
                "subject": "群聊（大江）",
                "packet_id": 40
            },
            "amount": "20.00",
            "channel": "wallet",
            "subject": "群聊（大江）",
            "status": 1,
            "succeed_at": "2019-12-24 13:33:26"
        },
        "in_out_type": 0,
        "type": 4,
        "created_at": "2019-12-24 13:33:26"
    },
    "ok": 1
}
```

#### 红包退换

```json
{
    "data": {
        "id": 209,
        "user": {
            "id": 20,
            "tx_id": "c4c2452c1214",
            "accid": "yx_20",
            "name": "obacmss",
            "avatar": "https://api.wtdoe.com/storage/default_avatars/pic_020.jpg",
            "bio": ""
        },
        "subject": "红包退还",
        "actual_amount": "20.00",
        "waterable": {
            "id": 108,
            "user_id": 20,
            "order_no": "20191224133326758187",
            "trade_no": null,
            "data": {
                "type": 1,
                "subject": "群聊（大江）",
                "packet_id": 40
            },
            "amount": "20.00",
            "channel": "wallet",
            "subject": "红包退还",
            "status": 1,
            "succeed_at": "2019-12-24 13:33:26"
        },
        "in_out_type": 1,
        "type": 5,
        "created_at": "2019-12-24 13:33:26"
    },
    "ok": 1
}
```

#### 红包进账

```json
{
    "data": {
        "id": 209,
        "user": {
            "id": 20,
            "tx_id": "c4c2452c1214",
            "accid": "yx_20",
            "name": "obacmss",
            "avatar": "https://api.wtdoe.com/storage/default_avatars/pic_020.jpg",
            "bio": ""
        },
        "subject": "群聊（大江）",
        "actual_amount": "20.00",
        "waterable": {
            "id": 108,
            "user_id": 20,
            "order_no": "20191224133326758187",
            "trade_no": null,
            "data": {
                "type": 1,
                "subject": "群聊（大江）",
                "packet_id": 40
            },
            "amount": "20.00",
            "channel": "wallet",
            "subject": "群聊（大江）",
            "status": 1,
            "succeed_at": "2019-12-24 13:33:26"
        },
        "in_out_type": 1,
        "type": 6,
        "created_at": "2019-12-24 13:33:26"
    },
    "ok": 1
}
```

#### 充值

```json
{
    "data": {
        "id": 222,
        "user": {
            "id": 24,
            "tx_id": "8b424303e54d",
            "accid": "yx_24",
            "name": "贾海然",
            "avatar": "https://zchat-app-image.oss-cn-zhangjiakou.aliyuncs.com/iKrExzEuurMk4fSs5xMSaqWYCclM7IBDJ8uy4ZJx.jpeg",
            "bio": "don't worry be happy"
        },
        "subject": "充值",
        "actual_amount": "0.02",
        "waterable": {
            "id": 116,
            "user_id": 24,
            "order_no": "20191224153154528652",
            "trade_no": "20191224153154528652",
            "data": {
                "buyer_id": "碧云天",
                "gmt_payment": "2019-12-24 15:35:42"
            },
            "amount": "0.02",
            "channel": "alipay",
            "subject": "充值",
            "status": 1,
            "succeed_at": "2019-12-24 15:35:42"
        },
        "in_out_type": 1,
        "type": 1,
        "created_at": "2019-12-24 15:35:42"
    },
    "ok": 1
}
```

#### 任务赏金 支付

```json
{
    "data": {
        "id": 232,
        "user": {
            "id": 20,
            "tx_id": "c4c2452c1214",
            "accid": "yx_20",
            "name": "obacmss",
            "avatar": "https://api.wtdoe.com/storage/default_avatars/pic_020.jpg",
            "bio": ""
        },
        "subject": "任务赏金",
        "actual_amount": "5.00",
        "waterable": {
            "id": 105,
            "user_id": 20,
            "order_no": "20191224163722163113",
            "data": {
                "title": "暮霭沉沉楚天阔",
                "task_id": 139
            },
            "amount": "5.00",
            "channel": "wallet",
            "subject": "任务赏金",
            "status": 1,
            "succeed_at": "2019-12-24 16:37:25"
        },
        "in_out_type": 0,
        "type": 3,
        "created_at": "2019-12-24 16:37:25"
    },
    "ok": 1
}
```

#### 任务赏金 退还

```json
{
    "data": {
        "id": 232,
        "user": {
            "id": 20,
            "tx_id": "c4c2452c1214",
            "accid": "yx_20",
            "name": "obacmss",
            "avatar": "https://api.wtdoe.com/storage/default_avatars/pic_020.jpg",
            "bio": ""
        },
        "subject": "任务已失效，赏金退换",
        "actual_amount": "5.00",
        "waterable": {
            "id": 105,
            "user_id": 20,
            "order_no": "20191224163722163113",
            "data": {
                "title": "暮霭沉沉楚天阔",
                "task_id": 139
            },
            "amount": "5.00",
            "channel": "wallet",
            "subject": "任务已失效，赏金退换",
            "status": 1,
            "succeed_at": "2019-12-24 16:37:25"
        },
        "in_out_type": 0,
        "type": 7,
        "created_at": "2019-12-24 16:37:25"
    },
    "ok": 1
}
```

#### 任务赏金 进账

```json
{
    "data": {
        "id": 232,
        "user": {
            "id": 20,
            "tx_id": "c4c2452c1214",
            "accid": "yx_20",
            "name": "obacmss",
            "avatar": "https://api.wtdoe.com/storage/default_avatars/pic_020.jpg",
            "bio": ""
        },
        "subject": "任务赏金",
        "actual_amount": "5.00",
        "waterable": {
            "id": 105,
            "user_id": 20,
            "order_no": "20191224163722163113",
            "data": {
                "title": "暮霭沉沉楚天阔",
                "task_id": 139
            },
            "amount": "5.00",
            "channel": "wallet",
            "subject": "任务赏金",
            "status": 1,
            "succeed_at": "2019-12-24 16:37:25"
        },
        "in_out_type": 0,
        "type": 8,
        "created_at": "2019-12-24 16:37:25"
    },
    "ok": 1
}
```
