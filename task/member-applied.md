# 我的投递

我的任务-我的投递

## 请求地址

> `tasks/member/applied`

## 请求类型

> `GET`

## 响应示例

> - `order` `json` 订单信息
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
            "id": 13,
            "task_no": "TS_20191125094857167781",
            "user": {
                "id": 1,
                "tx_id": "f3d0d305f962",
                "accid": "yx_1",
                "name": "obacmss",
                "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
                "bio": "",
                "level": 0
            },
            "title": "上门修理电脑",
            "order": "",
            "applier": {
                "id": 2,
                "tx_id": "21cf8bd04e7e",
                "accid": "yx_2",
                "name": "21cf8bd04e7e",
                "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
                "bio": "",
                "level": 0
            },
            "hire_amount": "30.00",
            "fee_amount": "0.00",
            "node": 2,
            "mode": 1,
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 104.07642,
            "latitude": 38.6518,
            "citycode": "0411",
            "description": "电脑开不开机",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 6,
            "views_count": 0,
            "has_fee_amount": false,
            "start_at": "2019-11-25 17:00:00",
            "end_at": "2019-11-25 20:00:00",
            "published_at": "2019-11-25 09:48:57",
            "paid_at": "",
            "applied_at": "2019-11-25 09:56:05",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "2019-11-25 10:24:51",
            "created_at": "2019-11-25 09:48:57",
            "process": {
                "has_published": true,
                "has_paid": false,
                "has_applied": true,
                "has_canceled": true,
                "has_completed": false,
                "has_confirmed": false,
                "has_invalided": true
            }
        },
        {
            "id": 16,
            "task_no": "TS_20191125102718487535",
            "user": {
                "id": 1,
                "tx_id": "f3d0d305f962",
                "accid": "yx_1",
                "name": "obacmss",
                "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
                "bio": "",
                "level": 0
            },
            "title": "上门修理电脑",
            "order": {
                "id": 12,
                "order_no": "20191125102718878308",
                "amount": "45.00",
                "currency": "CNY",
                "type": 3,
                "subject": "任务赏金",
                "body": "",
                "actual_amount": "45.00",
                "channel": "wallet",
                "status": 2,
                "orderable_id": 16,
                "orderable_type": "task",
                "succeed_at": "2019-11-25 10:30:18",
                "canceled_at": "",
                "created_at": "2019-11-25 10:27:18",
                "has_succeed": true,
                "has_expired": true,
                "has_canceled": false,
                "has_refunded": true
            },
            "applier": {
                "id": 2,
                "tx_id": "21cf8bd04e7e",
                "accid": "yx_2",
                "name": "21cf8bd04e7e",
                "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
                "bio": "",
                "level": 0
            },
            "hire_amount": "20.00",
            "fee_amount": "45.00",
            "node": 2,
            "mode": 1,
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 104.07642,
            "latitude": 38.6518,
            "citycode": "0411",
            "description": "电脑开不开机",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 6,
            "views_count": 0,
            "has_fee_amount": true,
            "start_at": "2019-11-25 17:00:00",
            "end_at": "2019-11-25 20:00:00",
            "published_at": "2019-11-25 10:30:18",
            "paid_at": "2019-11-25 10:30:18",
            "applied_at": "2019-11-25 10:31:11",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "2019-11-25 10:34:07",
            "created_at": "2019-11-25 10:27:18",
            "process": {
                "has_published": true,
                "has_paid": true,
                "has_applied": true,
                "has_canceled": true,
                "has_completed": false,
                "has_confirmed": false,
                "has_invalided": true
            }
        },
        {
            "id": 17,
            "task_no": "TS_20191125103220618964",
            "user": {
                "id": 1,
                "tx_id": "f3d0d305f962",
                "accid": "yx_1",
                "name": "obacmss",
                "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
                "bio": "",
                "level": 0
            },
            "title": "上门修理电脑",
            "order": {
                "id": 13,
                "order_no": "20191125103220902964",
                "amount": "45.00",
                "currency": "CNY",
                "type": 3,
                "subject": "任务赏金",
                "body": "",
                "actual_amount": "45.00",
                "channel": "wallet",
                "status": 2,
                "orderable_id": 17,
                "orderable_type": "task",
                "succeed_at": "2019-11-25 10:35:50",
                "canceled_at": "",
                "created_at": "2019-11-25 10:32:20",
                "has_succeed": true,
                "has_expired": true,
                "has_canceled": false,
                "has_refunded": true
            },
            "applier": {
                "id": 2,
                "tx_id": "21cf8bd04e7e",
                "accid": "yx_2",
                "name": "21cf8bd04e7e",
                "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
                "bio": "",
                "level": 0
            },
            "hire_amount": "20.00",
            "fee_amount": "45.00",
            "node": 2,
            "mode": 1,
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 104.07642,
            "latitude": 38.6518,
            "citycode": "0411",
            "description": "电脑开不开机",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 6,
            "views_count": 0,
            "has_fee_amount": true,
            "start_at": "2019-11-25 17:00:00",
            "end_at": "2019-11-25 20:00:00",
            "published_at": "2019-11-25 10:35:50",
            "paid_at": "2019-11-25 10:35:50",
            "applied_at": "2019-11-25 10:36:11",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "2019-11-25 10:36:30",
            "created_at": "2019-11-25 10:32:20",
            "process": {
                "has_published": true,
                "has_paid": true,
                "has_applied": true,
                "has_canceled": true,
                "has_completed": false,
                "has_confirmed": false,
                "has_invalided": true
            }
        },
        {
            "id": 18,
            "task_no": "TS_20191125103757764562",
            "user": {
                "id": 1,
                "tx_id": "f3d0d305f962",
                "accid": "yx_1",
                "name": "obacmss",
                "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
                "bio": "",
                "level": 0
            },
            "title": "上门修理电脑",
            "order": {
                "id": 14,
                "order_no": "20191125103757216967",
                "amount": "45.00",
                "currency": "CNY",
                "type": 3,
                "subject": "任务赏金",
                "body": "",
                "actual_amount": "45.00",
                "channel": "wallet",
                "status": 5,
                "orderable_id": 18,
                "orderable_type": "task",
                "succeed_at": "2019-11-25 10:38:15",
                "canceled_at": "",
                "created_at": "2019-11-25 10:37:57",
                "has_succeed": true,
                "has_expired": true,
                "has_canceled": false,
                "has_refunded": false
            },
            "applier": {
                "id": 2,
                "tx_id": "21cf8bd04e7e",
                "accid": "yx_2",
                "name": "21cf8bd04e7e",
                "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
                "bio": "",
                "level": 0
            },
            "hire_amount": "20.00",
            "fee_amount": "45.00",
            "node": 2,
            "mode": 1,
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 104.07642,
            "latitude": 38.6518,
            "citycode": "0411",
            "description": "电脑开不开机",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 7,
            "views_count": 0,
            "has_fee_amount": true,
            "start_at": "2019-11-25 17:00:00",
            "end_at": "2019-11-25 20:00:00",
            "published_at": "2019-11-25 10:38:15",
            "paid_at": "2019-11-25 10:38:15",
            "applied_at": "2019-11-25 10:49:02",
            "completed_at": "2019-11-25 10:49:48",
            "confirmed_at": "2019-11-25 11:11:09",
            "canceled_at": "",
            "created_at": "2019-11-25 10:37:57",
            "process": {
                "has_published": true,
                "has_paid": true,
                "has_applied": true,
                "has_canceled": false,
                "has_completed": true,
                "has_confirmed": true,
                "has_invalided": false
            }
        }
    ],
    "links": {
        "first": "http://api.tongxun.test/api/tasks/member/applied?page=1",
        "last": "http://api.tongxun.test/api/tasks/member/applied?page=1",
        "prev": null,
        "next": null
    },
    "meta": {
        "current_page": 1,
        "from": 1,
        "last_page": 1,
        "path": "http://api.tongxun.test/api/tasks/member/applied",
        "per_page": 15,
        "to": 4,
        "total": 4
    },
    "ok": 1
}
```