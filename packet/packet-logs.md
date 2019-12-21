# 红包记录

红包收发列表

## 请求地址

> `packets`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Query

> - `type` 类型 `1: 收到的，2：发的`
> - `date` 年份 `2018, 2019`

## 响应示例

```json
{
    "data": [
        {
            "id": 9,
            "amount": "20.00",
            "subject": "obacmss",
            "created_at": "2019-12-20 11:33:08"
        }
    ],
    "links": {
        "first": "https://api.wtdoe.com/api/packets?page=1",
        "last": "https://api.wtdoe.com/api/packets?page=1",
        "prev": null,
        "next": null
    },
    "meta": {
        "current_page": 1,
        "from": 1,
        "last_page": 1,
        "path": "https://api.wtdoe.com/api/packets",
        "per_page": 15,
        "to": 1,
        "total": 1
    },
    "sums": {
        "total_amount": "20.00",
        "total_count": 1
    },
    "ok": 1
}
```