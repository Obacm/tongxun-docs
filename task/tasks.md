# 全部任务

我的任务-全部任务

## 请求地址

> `tasks/filter`

## 请求类型

> `GET`

## 请求参数

#### Query

> - `latitude` `string` 纬度  `必需传`
> - `longitude` `string` 经度 `必需传`
> - `filter` `string` 查询条件 `必需传` `multiple: 综合，distance: 距离, fee: 赏金, published: 发布时间, hire: 佣金` 
> - `node` `string` 任务分类
> - `sort` `string` 排序 `desc: 降序， asc: 升序` `发布时间 && 佣金有排序参数`

## 响应示例

> - `distance` `float` 距离
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
            "id": 11,
            "task_no": "TS_20191128164535188725",
            "user": {
                "id": 1,
                "tx_id": "f3d0d305f962",
                "accid": "yx_1",
                "name": "obacmss",
                "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
                "bio": "",
                "level": 0
            },
            "title": "测试排序0333",
            "hire_amount": "20.00",
            "fee_amount": "30.00",
            "node": 2,
            "mode": 1,
            "address": "辽宁省大连市甘井子区 红岭校区1-5-606",
            "longitude": 120.522736,
            "latitude": 37.23783,
            "citycode": "0411",
            "position": {
                "type": "Point",
                "coordinates": [
                    120.522736,
                    37.23783
                ]
            },
            "distance": 201.29,
            "description": "测试排序023333",
            "pics": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "state": 1,
            "views_count": 0,
            "has_fee_amount": true,
            "start_at": "2019-11-29 14:50:00",
            "end_at": "2019-11-30 15:30:00",
            "published_at": "2019-11-28 16:45:54",
            "paid_at": "2019-11-28 16:45:54",
            "applied_at": "",
            "completed_at": "",
            "confirmed_at": "",
            "canceled_at": "",
            "created_at": "2019-11-28 16:45:35",
            "process": {
                "has_published": true,
                "has_paid": true,
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
        "last": "http://api.tongxun.test/api/tasks/filter?page=26",
        "prev": "http://api.tongxun.test/api/tasks/filter?page=1",
        "next": "http://api.tongxun.test/api/tasks/filter?page=3"
    },
    "meta": {
        "current_page": 2,
        "from": 2,
        "last_page": 26,
        "path": "http://api.tongxun.test/api/tasks/filter",
        "per_page": 1,
        "to": 2,
        "total": 26
    },
    "ok": 1
}
```
