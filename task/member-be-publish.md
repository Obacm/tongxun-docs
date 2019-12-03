# 待发布

我的任务-待发布

## 请求地址

> `tasks/member/be_publish`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应示例

> - `order` `json` 订单信息
> - `has_fee_amount` `bool` 是否有赏金
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
    "data": [
        {
            "id": 23,
            "task_no": "TS_20191126114041151998",
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
            "applier": "",
            "hire_amount": "30.00",
            "fee_amount": "0.00",
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 104.07642,
            "latitude": 38.6518,
            "citycode": "0411",
            "description": "电脑开不开机",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 0,
            "views_count": 0,
            "has_fee_amount": false,
            "is_owner": true,
            "start_at": "2019-11-27 17:00:00",
            "end_at": "2019-11-27 20:00:00",
            "published_at": "",
            "paid_at": "",
            "applied_at": "",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "",
            "created_at": "2019-11-26 11:40:41",
            "process": {
                "has_published": false,
                "has_paid": false,
                "has_applied": false,
                "has_canceled": false,
                "has_completed": false,
                "has_confirmed": false,
                "has_invalided": false,
                "has_commented": false
            }
        }
    ],
    "links": {
        "first": "http://api.tongxun.test/api/tasks/member/be_publish?page=1",
        "last": "http://api.tongxun.test/api/tasks/member/be_publish?page=1",
        "prev": null,
        "next": null
    },
    "meta": {
        "current_page": 1,
        "from": 1,
        "last_page": 1,
        "path": "http://api.tongxun.test/api/tasks/member/be_publish",
        "per_page": 15,
        "to": 1,
        "total": 1
    },
    "ok": 1
}
```