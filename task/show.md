# 任务详情

任务详情

## 请求地址

> `task/[id]`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应示例

> - `order` `json` 订单信息
> - `evidences` `array` 完成任务的图片
> - `has_fee_amount` `bool` 是否有赏金
> - `has_favorited` `bool` 是否有收藏
> - `is_owner` `bool` 是否是任务所有者
> - `has_published` `bool` 是否已发布
> - `has_completed` `bool` 是否已申请完成
> - `has_confirmed` `bool` 是否已确定完成
> - `has_canceled` `bool` 是否已取消任务
> - `has_invalided` `bool` 是否已失效
> - `has_commented` `bool` 是否评论
> - `state` `int` 任务状态 `0: 草稿， 1: 已发布，2: 待支付，3: 已删除，4: 已取消发布， 5: 待完成，6: 已取消，7: 已完成申请, 8: 已确定完成`

```json
{
    "data": {
        "id": 18,
        "task_no": "TS_20191125103757764562",
        "user": {
            "id": 1,
            "tx_id": "f3d0d305f962",
            "accid": "yx_1",
            "name": "obacmss",
            "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": 5,
            "last_actived_at": "4小时前活跃"
        },
        "applier": {
            "id": 2,
            "tx_id": "21cf8bd04e7e",
            "accid": "yx_2",
            "name": "21cf8bd04e7e",
            "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "bio": "",
            "level": 0,
            "score": "2.0",
            "last_actived_at": "4小时前活跃"
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
            "state": 5,
            "orderable_id": 18,
            "orderable_type": "task",
            "succeed_at": "2019-11-25 10:38:15",
            "canceled_at": "",
            "created_at": "2019-11-25 10:37:57",
            "has_succeed": true,
            "has_expired": false,
            "has_canceled": false,
            "has_refunded": false
        },
        "hire_amount": "20.00",
        "fee_amount": "45.00",
        "node": {
            "id": 2,
            "name": "家政服务",
            "hot": 0
        },
        "mode": {
            "id": 1,
            "name": "鲜花"
        },
        "site_id": 20,
        "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
        "longitude": 104.07642,
        "latitude": 38.6518,
        "citycode": "0411",
        "description": "电脑开不开机",
        "pics": [
            "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
            "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
        ],
        "evidences": [
            "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
            "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
        ],
        "state": 7,
        "views_count": 0,
        "has_fee_amount": true,
        "has_favorited": false,
        "is_owner": true,
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
            "has_invalided": false,
            "has_commented": false
        }
    },
    "ok": 1
}
```