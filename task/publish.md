# 任务发布

创建一个有效的任务

## 请求地址

> `task/publish`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `id` `int` 任务ID `可选参数，存在: 更新当前任务信息并发布，不存在: 发布新的任务`
> - `title` `string` 标题
> - `hire_amount` `decimal` 佣金
> - `fee_amount` `decimal` 赏金
> - `node` `int` 一级分类
> - `mode` `int` 二级分类
> - `site_id` `int` 地址ID
> - `description` `string` 描述
> - `pics` `array` 图片
> - `start_at` `string` 开始时间
> - `end_at` `string` 结束时间

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
    "data": {
        "id": 19,
        "task_no": "TS_20191125111546821191",
        "user": {
            "id": 1,
            "tx_id": "f3d0d305f962",
            "accid": "yx_1",
            "name": "obacmss",
            "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "description": "",
            "level": 0
        },
        "applier": "",
        "title": "上门修理电脑",
        "order": {
            "id": 15,
            "order_no": "20191125111546969251",
            "amount": "45.00",
            "currency": "CNY",
            "type": 3,
            "subject": "任务赏金",
            "body": "",
            "actual_amount": "45.00",
            "channel": "wallet",
            "state": 0,
            "orderable_id": 19,
            "orderable_type": "task",
            "succeed_at": "",
            "canceled_at": "",
            "created_at": "2019-11-25 11:15:46",
            "has_succeed": false,
            "has_expired": false,
            "has_canceled": false,
            "has_refunded": false
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
        "state": 2,
        "views_count": 0,
        "has_fee_amount": true,
        "start_at": "2019-11-25 17:00:00",
        "end_at": "2019-11-25 20:00:00",
        "published_at": "",
        "paid_at": "",
        "applied_at": "",
        "completed_at": "",
        "confirmed_at": "",
        "canceled_at": "",
        "created_at": "2019-11-25 11:15:46",
        "process": {
            "has_published": true,
            "has_paid": false,
            "has_applied": false,
            "has_completed": false,
            "has_confirmed": false,
            "has_canceled": false,
            "has_invalided": false
        }
    },
    "ok": 1
}
```

```json
{
    "data": {
        "id": 21,
        "task_no": "TS_20191125143711330844",
        "user": {
            "id": 1,
            "tx_id": "f3d0d305f962",
            "accid": "yx_1",
            "name": "obacmss",
            "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "description": "",
            "level": 0
        },
        "applier": "",
        "title": "上门修理电脑",
        "order": "",
        "hire_amount": "20.00",
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
        "state": 1,
        "views_count": 0,
        "has_fee_amount": false,
        "start_at": "2019-11-25 17:00:00",
        "end_at": "2019-11-25 20:00:00",
        "published_at": "2019-11-25 14:37:11",
        "paid_at": "",
        "applied_at": "",
        "completed_at": "",
        "confirmed_at": "",
        "canceled_at": "",
        "created_at": "2019-11-25 14:37:11",
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
    "ok": 1
}
```