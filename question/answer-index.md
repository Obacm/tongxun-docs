# 回答列表

回答列表

## 请求地址

> `answer/index`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

```json
{
     "data": [
            {
                "id": 2,
                "question_id": 2,
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
                    "last_actived_at": "2019-12-20T06:16:09.000000Z"
                },
                "content": "测试回答123456",
                "image": [
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                ],
                "reply_count": 0,
                "praise_count": 0,
                "question": {
                    "id": 2,
                    "title": "测试标题2",
                    "content": "测试内容2",
                    "image": [
                        "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                        "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                    ],
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
                    "category_id": 6,
                    "answer_count": 1,
                    "created_at": "2019-12-13 10:26:11",
                    "updated_at": "2019-12-13 10:28:23"
                },
                "comment": [],
                "created_at": "2019-12-13 10:28:23",
                "updated_at": "2019-12-13 10:28:23"
            }
        ],
        "links": {
            "first": "http://tongxun.test/api/answer/index?page=1",
            "last": "http://tongxun.test/api/answer/index?page=1",
            "prev": null,
            "next": null
        },
        "meta": {
            "current_page": 1,
            "from": 1,
            "last_page": 1,
            "path": "http://tongxun.test/api/answer/index",
            "per_page": 10,
            "to": 1,
            "total": 1
        },
        "ok": 1
}
```