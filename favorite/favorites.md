# 收藏的任务列表

收藏的任务

## 请求地址

> `favorites`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Query

> - `position` `string` 纬经度  `可选参数` `120.522736,38.86783` `经度在前，纬度在后`

## 响应示例

> - `title` `string` 标题
> - `hire_amount` `string` 佣金
> - `fee_amount` `string` 赏金
> - `fee_amount` `string` 赏金
> - `address` `string` 地址
> - `pics` `array` 图片
> - `start_at` `string` 起始时间
> - `end_at` `string` 结束时间
> - `published_at` `string` 发布时间
> - `has_fee_amount` `bool` 是否有赏金
> - `has_published` `bool` 是否已发布
> - `has_completed` `bool` 是否已申请完成
> - `has_confirmed` `bool` 是否已确定完成
> - `has_canceled` `bool` 是否已取消任务
> - `has_invalided` `bool` 是否已失效
> - `state` `int` 任务状态 `0: 草稿， 1: 已发布，2: 待支付，3: 已删除，4: 已取消发布， 5: 待完成，6: 已取消，7: 已完成申请, 8: 已确定完成`

```json
{
    "data": [
        {
            "id": 19,
            "task_no": "TS_20200312155846430179",
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
            "title": "测试队列66",
            "hire_amount": "10.00",
            "fee_amount": "0.00",
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 122.98,
            "latitude": 39.7,
            "citycode": "0411",
            "position": {
                "type": "Point",
                "coordinates": [
                    122.98,
                    39.7
                ]
            },
            "description": "测试队列66",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 1,
            "views_count": 0,
            "has_fee_amount": false,
            "start_at": "2020-04-27 15:25:00",
            "end_at": "2020-04-27 15:30:00",
            "published_at": "2020-03-12 15:58:46",
            "paid_at": "",
            "applied_at": "",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "",
            "created_at": "2020-03-12 15:58:46",
            "process": {
                "has_published": true,
                "has_paid": false,
                "has_applied": false,
                "has_canceled": false,
                "has_completed": false,
                "has_confirmed": false,
                "has_invalided": false,
                "has_commented": false
            }
        },
        {
            "id": 17,
            "task_no": "TS_20200110152354785474",
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
            "title": "测试活动日志",
            "hire_amount": "10.00",
            "fee_amount": "12.00",
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 122.98,
            "latitude": 39.7,
            "citycode": "0411",
            "position": {
                "type": "Point",
                "coordinates": [
                    122.98,
                    39.7
                ]
            },
            "description": "测试活动日志",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 9,
            "views_count": 0,
            "has_fee_amount": true,
            "start_at": "2020-01-15 15:25:00",
            "end_at": "2020-01-16 15:25:00",
            "published_at": "2020-01-10 15:24:19",
            "paid_at": "2020-01-10 15:24:19",
            "applied_at": "",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "",
            "created_at": "2020-01-10 15:23:54",
            "process": {
                "has_published": true,
                "has_paid": true,
                "has_applied": false,
                "has_canceled": false,
                "has_completed": false,
                "has_confirmed": false,
                "has_invalided": true,
                "has_commented": false
            }
        },
        {
            "id": 16,
            "task_no": "TS_20200110152315941608",
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
            "title": "测试活动日志",
            "hire_amount": "10.00",
            "fee_amount": "12.00",
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 122.98,
            "latitude": 39.7,
            "citycode": "0411",
            "position": {
                "type": "Point",
                "coordinates": [
                    122.98,
                    39.7
                ]
            },
            "description": "测试活动日志",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 9,
            "views_count": 0,
            "has_fee_amount": true,
            "start_at": "2020-01-15 15:25:00",
            "end_at": "2020-01-16 15:25:00",
            "published_at": "2020-01-10 15:23:21",
            "paid_at": "2020-01-10 15:23:21",
            "applied_at": "",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "",
            "created_at": "2020-01-10 15:23:15",
            "process": {
                "has_published": true,
                "has_paid": true,
                "has_applied": false,
                "has_canceled": false,
                "has_completed": false,
                "has_confirmed": false,
                "has_invalided": true,
                "has_commented": false
            }
        }
    ],
    "links": {
        "first": "http://api.tongxun.test/api/favorites?page=1",
        "last": "http://api.tongxun.test/api/favorites?page=1",
        "prev": null,
        "next": null
    },
    "meta": {
        "current_page": 1,
        "from": 1,
        "last_page": 1,
        "path": "http://api.tongxun.test/api/favorites",
        "per_page": 15,
        "to": 3,
        "total": 3
    },
    "ok": 1
}
```
