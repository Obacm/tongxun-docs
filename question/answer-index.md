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
                "id": 1,
                "question_id": 1,
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
                    "last_actived_at": "2019-12-11T07:33:33.000000Z"
                },
                "content": "测试内容88",
                "image": [
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                ],
                "reply_count": 9,
                "praise_count": 0,
                "created_at": "2019-12-05 10:37:07",
                "updated_at": "2019-12-09 11:15:43"
            },
            {
                "id": 3,
                "question_id": 1,
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
                    "last_actived_at": "2019-12-11T07:33:33.000000Z"
                },
                "content": "测试回答 哈哈",
                "image": [
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                ],
                "reply_count": 0,
                "praise_count": 0,
                "created_at": "2019-12-05 10:41:37",
                "updated_at": "2019-12-05 10:41:37"
            },
            {
                "id": 5,
                "question_id": 1,
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
                    "last_actived_at": "2019-12-11T07:33:33.000000Z"
                },
                "content": "测试回答 哈哈",
                "image": [
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                ],
                "reply_count": 0,
                "praise_count": 0,
                "created_at": "2019-12-05 10:50:40",
                "updated_at": "2019-12-05 10:50:40"
            },
            {
                "id": 6,
                "question_id": 1,
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
                    "last_actived_at": "2019-12-11T07:33:33.000000Z"
                },
                "content": "测试回答 哈哈",
                "image": [
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                ],
                "reply_count": 0,
                "praise_count": 0,
                "created_at": "2019-12-05 10:53:34",
                "updated_at": "2019-12-05 10:53:34"
            },
            {
                "id": 11,
                "question_id": 9,
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
                    "last_actived_at": "2019-12-11T07:33:33.000000Z"
                },
                "content": "测试回答123456",
                "image": [
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                ],
                "reply_count": 1,
                "praise_count": 0,
                "created_at": "2019-12-09 14:08:24",
                "updated_at": "2019-12-09 14:09:01"
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
            "to": 5,
            "total": 5
        },
        "ok": 1
}
```