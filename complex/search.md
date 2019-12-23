# 语音搜索 --- 任务 && 问答

根据文字检索任务与问答

## 请求地址

> `complex/search`

## 请求类型

> `GET`

## 请求参数

#### Query

> - `keyword` `string` 关键字

## 响应示例

```json
{
    "data": {
        "tasks": [
            {
                "id": 10,
                "task_no": "TS_20191218172834940649",
                "title": "嘻嘻哈哈哈哈",
                "hire_amount": "10.00",
                "fee_amount": "0.00",
                "description": "卧槽这的可以这个",
                "state": 1,
                "has_fee_amount": false,
                "published_at": "2019-12-18 17:28:34"
            },
            {
                "id": 11,
                "task_no": "TS_20191218173011586466",
                "title": "嘻嘻哈哈哈哈",
                "hire_amount": "10.00",
                "fee_amount": "0.00",
                "description": "卧槽这的可以这个",
                "state": 1,
                "has_fee_amount": false,
                "published_at": "2019-12-18 17:30:11"
            }
        ],
        "questions": [
            {
                "id": 4,
                "title": "家里卫生间贴瓷砖",
                "content": "需要一个瓦工",
                "image": [
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                ],
                "user": {
                    "id": 1,
                    "name": "王大力",
                    "mobile": "15898146121",
                    "avatar": "",
                    "level": 0,
                    "birthday": "",
                    "province": "",
                    "city": "",
                    "site_id": null,
                    "gender": "male",
                    "settings": {
                        "push_notify": 1,
                        "email_notify": 1
                    },
                    "accid": "yx_1",
                    "has_idcard_verified": false,
                    "has_payee_verified": false,
                    "has_pay_password": false,
                    "last_actived_at": "2019-12-23T09:42:21.000000Z"
                },
                "category_id": 6,
                "answer_count": 0,
                "created_at": "2019-12-21 10:18:03",
                "updated_at": "2019-12-21 10:18:03"
            }
        ]
    },
    "ok": 1
}
```
