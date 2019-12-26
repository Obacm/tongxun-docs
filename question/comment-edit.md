# 回答评论列表

获取回答评论列表

## 请求地址

> `comment/[id]/edit`

## 请求类型

> `GET`

## 请求参数

## 响应示例

```json
{
    "data": [
            {
                "id": 4,
                "answer_id": 1,
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
                    "last_actived_at": "2019-12-26T06:33:35.000000Z"
                },
                "content": "测试评论888",
                "praise_count": 0,
                "created_at": "2019-12-18 15:49:22",
                "updated_at": "2019-12-18 15:49:22"
            },
            {
                "id": 1,
                "answer_id": 1,
                "user": {
                    "id": 2,
                    "name": "刘铁柱",
                    "mobile": "15898146122",
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
                    "accid": "yx_2",
                    "has_idcard_verified": false,
                    "has_payee_verified": false,
                    "has_pay_password": false,
                    "last_actived_at": "2019-12-07T01:19:01.000000Z"
                },
                "content": "测试评论52",
                "praise_count": 0,
                "created_at": "2019-12-13 10:31:37",
                "updated_at": "2019-12-13 10:31:37"
            }
        ],
        "links": {
            "first": "http://tongxun.test/api/comment/1/edit?page=1",
            "last": "http://tongxun.test/api/comment/1/edit?page=1",
            "prev": null,
            "next": null
        },
        "meta": {
            "current_page": 1,
            "from": 1,
            "last_page": 1,
            "path": "http://tongxun.test/api/comment/1/edit",
            "per_page": 10,
            "to": 2,
            "total": 2
        },
        "ok": 1
}
```

