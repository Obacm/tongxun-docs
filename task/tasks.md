# 任务圈

任务圈 根据查询条件查询任务列表

## 请求地址

> `tasks/filter`

## 请求类型

> `GET`

## 请求参数

#### Query

> - `position` `string` 纬经度  `可选参数` `120.522736,38.86783` `经度在前，纬度在后`
> - `filter` `string` 查询条件 `必需传` `multiple: 综合，distance: 距离, fee: 赏金, published: 发布时间, hire: 佣金` 
> - `node` `int` 一级分类 `可选参数` 
> - `mode` `int` 二级分类 `可选参数` 
> - `sort` `string` 排序 `可选参数`  `desc: 降序， asc: 升序` `发布时间 && 佣金有排序参数`

## 响应示例

> - `title` `string` 标题
> - `hire_amount` `string` 佣金
> - `fee_amount` `string` 赏金
> - `fee_amount` `string` 赏金
> - `address` `string` 地址
> - `node` `int` 一级分类
> - `mode` `int` 二级分类
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
            "id": 30,
            "task_no": "TS_20191129093636338102",
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
            "title": "测试队列66",
            "hire_amount": "10.00",
            "fee_amount": "0.00",
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 110.522736,
            "latitude": 31.23783,
            "citycode": "0411",
            "position": {
                "type": "Point",
                "coordinates": [
                    110.522736,
                    31.23783
                ]
            },
            "distance": 1310.61,
            "description": "测试队列66",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 1,
            "views_count": 0,
            "has_fee_amount": false,
            "start_at": "2019-11-29 15:25:00",
            "end_at": "2019-11-29 15:30:00",
            "published_at": "11-28 16:45",
            "paid_at": "",
            "applied_at": "",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "",
            "created_at": "2019-11-29 09:36:36",
            "process": {
                "has_published": true,
                "has_paid": false,
                "has_applied": false,
                "has_canceled": false,
                "has_completed": false,
                "has_confirmed": false,
                "has_invalided": false
            }
        },
        {
            "id": 29,
            "task_no": "TS_20191129093635185770",
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
            "title": "测试队列66",
            "hire_amount": "10.00",
            "fee_amount": "0.00",
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 110.522736,
            "latitude": 31.23783,
            "citycode": "0411",
            "position": {
                "type": "Point",
                "coordinates": [
                    110.522736,
                    31.23783
                ]
            },
            "distance": 1310.61,
            "description": "测试队列66",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 1,
            "views_count": 0,
            "has_fee_amount": false,
            "start_at": "2019-11-29 15:25:00",
            "end_at": "2019-11-29 15:30:00",
            "published_at": "11-28 16:45",
            "paid_at": "",
            "applied_at": "",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "",
            "created_at": "2019-11-29 09:36:35",
            "process": {
                "has_published": true,
                "has_paid": false,
                "has_applied": false,
                "has_canceled": false,
                "has_completed": false,
                "has_confirmed": false,
                "has_invalided": false
            }
        },
        {
            "id": 28,
            "task_no": "TS_20191129093633112334",
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
            "title": "测试队列66",
            "hire_amount": "10.00",
            "fee_amount": "0.00",
            "node": 2,
            "mode": 1,
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 110.522736,
            "latitude": 31.23783,
            "citycode": "0411",
            "position": {
                "type": "Point",
                "coordinates": [
                    110.522736,
                    31.23783
                ]
            },
            "distance": 1310.61,
            "description": "测试队列66",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 1,
            "views_count": 0,
            "has_fee_amount": false,
            "start_at": "2019-11-29 15:25:00",
            "end_at": "2019-11-29 15:30:00",
            "published_at": "11-28 16:45",
            "paid_at": "",
            "applied_at": "",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "",
            "created_at": "2019-11-29 09:36:33",
            "process": {
                "has_published": true,
                "has_paid": false,
                "has_applied": false,
                "has_canceled": false,
                "has_completed": false,
                "has_confirmed": false,
                "has_invalided": false
            }
        },
        {
            "id": 27,
            "task_no": "TS_20191129093632107714",
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
            "title": "测试队列66",
            "hire_amount": "10.00",
            "fee_amount": "0.00",
            "node": 2,
            "mode": 1,
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 110.522736,
            "latitude": 31.23783,
            "citycode": "0411",
            "position": {
                "type": "Point",
                "coordinates": [
                    110.522736,
                    31.23783
                ]
            },
            "distance": 1310.61,
            "description": "测试队列66",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 1,
            "views_count": 0,
            "has_fee_amount": false,
            "start_at": "2019-11-29 15:25:00",
            "end_at": "2019-11-29 15:30:00",
            "published_at": "11-28 16:45",
            "paid_at": "",
            "applied_at": "",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "",
            "created_at": "2019-11-29 09:36:32",
            "process": {
                "has_published": true,
                "has_paid": false,
                "has_applied": false,
                "has_canceled": false,
                "has_completed": false,
                "has_confirmed": false,
                "has_invalided": false
            }
        },
        {
            "id": 26,
            "task_no": "TS_20191129093630401142",
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
            "title": "测试队列66",
            "hire_amount": "10.00",
            "fee_amount": "0.00",
            "node": 2,
            "mode": 1,
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 110.522736,
            "latitude": 31.23783,
            "citycode": "0411",
            "position": {
                "type": "Point",
                "coordinates": [
                    110.522736,
                    31.23783
                ]
            },
            "distance": 1310.61,
            "description": "测试队列66",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 1,
            "views_count": 0,
            "has_fee_amount": false,
            "start_at": "2019-11-29 15:25:00",
            "end_at": "2019-11-29 15:30:00",
            "published_at": "11-28 16:45",
            "paid_at": "",
            "applied_at": "",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "",
            "created_at": "2019-11-29 09:36:30",
            "process": {
                "has_published": true,
                "has_paid": false,
                "has_applied": false,
                "has_canceled": false,
                "has_completed": false,
                "has_confirmed": false,
                "has_invalided": false
            }
        },
        {
            "id": 24,
            "task_no": "TS_20191129093627466742",
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
            "title": "测试队列66",
            "hire_amount": "10.00",
            "fee_amount": "0.00",
            "node": 2,
            "mode": 1,
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 110.522736,
            "latitude": 31.23783,
            "citycode": "0411",
            "position": {
                "type": "Point",
                "coordinates": [
                    110.522736,
                    31.23783
                ]
            },
            "distance": 1310.61,
            "description": "测试队列66",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 1,
            "views_count": 0,
            "has_fee_amount": false,
            "start_at": "2019-11-29 15:25:00",
            "end_at": "2019-11-29 15:30:00",
            "published_at": "11-28 16:45",
            "paid_at": "",
            "applied_at": "",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "",
            "created_at": "2019-11-29 09:36:27",
            "process": {
                "has_published": true,
                "has_paid": false,
                "has_applied": false,
                "has_canceled": false,
                "has_completed": false,
                "has_confirmed": false,
                "has_invalided": false
            }
        },
        {
            "id": 15,
            "task_no": "TS_20191129093614894239",
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
            "title": "测试队列66",
            "hire_amount": "10.00",
            "fee_amount": "0.00",
            "node": 2,
            "mode": 1,
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 110.522736,
            "latitude": 31.23783,
            "citycode": "0411",
            "position": {
                "type": "Point",
                "coordinates": [
                    110.522736,
                    31.23783
                ]
            },
            "distance": 1310.61,
            "description": "测试队列66",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 1,
            "views_count": 0,
            "has_fee_amount": false,
            "start_at": "2019-11-29 15:25:00",
            "end_at": "2019-11-29 15:30:00",
            "published_at": "11-28 16:45",
            "paid_at": "",
            "applied_at": "",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "",
            "created_at": "2019-11-29 09:36:14",
            "process": {
                "has_published": true,
                "has_paid": false,
                "has_applied": false,
                "has_canceled": false,
                "has_completed": false,
                "has_confirmed": false,
                "has_invalided": false
            }
        }   
    ],
    "links": {
        "first": "http://api.tongxun.test/api/tasks/filter?page=1",
        "last": "http://api.tongxun.test/api/tasks/filter?page=3",
        "prev": "http://api.tongxun.test/api/tasks/filter?page=1",
        "next": "http://api.tongxun.test/api/tasks/filter?page=3"
    },
    "meta": {
        "current_page": 2,
        "from": 11,
        "last_page": 3,
        "path": "http://api.tongxun.test/api/tasks/filter",
        "per_page": 10,
        "to": 20,
        "total": 26
    },
    "ok": 1
}
```
