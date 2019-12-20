# 红包详情

红包详情

## 请求地址

> `packets/[packet]`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应参数

> - `id` `int` 红包ID
> - `user` `json` 发红包人
> - `accid` `string` 云信ID
> - `title` `string` 红包主题
> - `type` `int` 红包所属类型
> - `count` `int` 红包个数
> - `remain_count` `int` 红包剩余个数
> - `total_amount` `string` 总金额
> - `remain_amount` `string` 剩余金额
> - `items` `json` 领取记录
> - `has_expired` `bool` 是否过期
> - `has_closed` `bool` 是否抢完

## 响应示例

```json
{
    "data": {
        "id": 10,
        "user": {
            "id": 7,
            "tx_id": "3e7c75082b41",
            "accid": "yx_7",
            "name": "3e7c75082b41",
            "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "5.0"
        },
        "to_accid": "yx_1",
        "title": "新年快乐",
        "type": 1,
        "count": 2,
        "remain_count": 0,
        "total_amount": "20.00",
        "remain_amount": "0.00",
        "items": [
            {
                "id": 7,
                "user": {
                    "id": 1,
                    "tx_id": "f3d0d305f962",
                    "accid": "yx_1",
                    "name": "obacmss",
                    "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
                    "bio": "",
                    "level": 0,
                    "score": "2.0"
                },
                "item_amount": "10.00",
                "created_at": "2019-12-20 10:24:48"
            },
            {
                "id": 9,
                "user": {
                    "id": 2,
                    "tx_id": "21cf8bd04e7e",
                    "accid": "yx_2",
                    "name": "21cf8bd04e7e",
                    "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
                    "bio": "",
                    "level": 0,
                    "score": "3.0"
                },
                "item_amount": "10.00",
                "created_at": "2019-12-20 14:00:16"
            }
        ],
        "has_expired": false,
        "has_closed": true
    },
    "ok": 1
}
```