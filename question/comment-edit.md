# 回答评论列表

获取回答评论列表

## 请求地址

> `comment/[id]/edit`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应示例

```json
{
    "data": [
            {
                "id": 1,
                "answer_id": 1,
                "user": {
                    "id": 1,
                    "name": "王大力",
                    "mobile": "15898146121",
                    "avatar": "",
                    "level": 0,
                    "score": null,
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
                    "last_actived_at": "2020-01-06T06:11:08.000000Z"
                },
                "content": "测试评论666",
                "praise_count": 12,
                "has_praised": false,
                "created_at": "2020-01-03 16:24:38",
                "updated_at": "2020-01-06 14:07:47"
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
            "to": 1,
            "total": 1
        },
        "ok": 1
}
```

