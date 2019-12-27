# 流水账

所有支付支出信息

## 请求地址

> `wallet/waters`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Query

> - `date` 日期 `2019-09`
> - `page` 页码 `不传默认第一页`

## 响应参数

> - `id` `int` 账单ID
> - `sums` `json` 总收入 支出
> - `user` `json` 用户信息
> - `subject` `string` 账单详情
> - `actual_amount` `string` 金额
> - `in_out_type` `int` 进出类型
> - `type` `int` 流水具体类型
> - `waterable_type` `string` 流水归属
> - `created_at` `string` 创建时间

## 响应示例

```json
{
    "data": [
        {
            "id": 2,
            "user": {
                "id": 1,
                "tx_id": "f3d0d305f962",
                "accid": "yx_1",
                "name": "obacmss",
                "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
                "description": "",
                "level": 0
            },
            "subject": "充值",
            "actual_amount": "0.01",
            "in_out_type": 1,
            "type": 1,
            "waterable_type": "wallet",
            "created_at": "2019-11-15 17:31:04"
        },
        {
            "id": 3,
            "user": {
                "id": 1,
                "tx_id": "f3d0d305f962",
                "accid": "yx_1",
                "name": "obacmss",
                "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
                "description": "",
                "level": 0
            },
            "subject": "任务赏金",
            "actual_amount": "0.01",
            "in_out_type": 1,
            "type": 1,
            "waterable_type": "task",
            "created_at": "2019-11-15 17:53:07"
        },
        {
            "id": 4,
            "user": {
                "id": 1,
                "tx_id": "f3d0d305f962",
                "accid": "yx_1",
                "name": "obacmss",
                "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
                "description": "",
                "level": 0
            },
            "subject": "大江",
            "actual_amount": "0.01",
            "in_out_type": 1,
            "type": 1,
            "waterable_type": "packet",
            "created_at": "2019-11-15 17:53:20"
        }
    ],
    "links": {
        "first": "http://api.tongxun.test/api/wallet/water?page=1",
        "last": "http://api.tongxun.test/api/wallet/water?page=1",
        "prev": null,
        "next": null
    },
    "meta": {
        "current_page": 1,
        "from": 1,
        "last_page": 1,
        "path": "http://api.tongxun.test/api/wallet/water",
        "per_page": 15,
        "to": 5,
        "total": 5
    },
    "sums": {
        "int_sum": "0.04",
        "out_sum": "0.01"
    },
    "ok": 1
}
```

## 异常示例

> - `日期参数必传`
> - `日期格式Y-m`

```json
{
    "errno": 10006,
    "msg": "日期参数必传",
    "ok": 0
}
```

