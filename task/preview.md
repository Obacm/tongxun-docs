# 任务圈-任务详情

任务详情，提供未登录情况下能够访问任务详情的能力

## 请求地址

> `tasks/[id]`

## 请求类型

> `GET`

## 响应示例

> - `has_fee_amount` `bool` 是否有赏金
> - `has_favorited` `bool` 是否有收藏
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
        "id": 17,
        "task_no": "TS_20191129093617791769",
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
        "title": "测试队列66",
        "hire_amount": "20.00",
        "fee_amount": "0.00",
        "node": {
            "id": 2,
            "name": "家政服务",
            "hot": 0
        },
        "mode": {
            "id": 1,
            "name": "鲜花"
        },
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
        "description": "测试队列66",
        "pics": [
            "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
            "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
        ],
        "state": 1,
        "views_count": 0,
        "has_fee_amount": false,
        "has_favorited": false,
        "start_at": "2019-11-29 15:25:00",
        "end_at": "2019-11-29 15:30:00",
        "published_at": "2019-11-29 09:36:17",
        "paid_at": "",
        "applied_at": "",
        "completed_at": "",
        "confirmed_at": "",
        "canceled_at": "",
        "created_at": "2019-11-29 09:36:17",
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
    "ok": 1
}
```