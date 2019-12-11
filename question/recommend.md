# 推荐列表

获取推荐列表

## 请求地址

> `question/recommend`

## 请求类型

> `GET`

## 请求参数

## 响应示例

```json
{
    "data": [
            {
                "id": 1,
                "title": "测试标题66",
                "content": "测试内容66",
                "image": [
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                ],
                "user_id": 1,
                "category_id": 6,
                "answer_count": 4,
                "user": {
                    "id": 1,
                    "tx_id": null,
                    "accid": "yx_1",
                    "name": "王大力",
                    "avatar": "",
                    "description": null,
                    "level": 0
                },
                "answer": {
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
                        "last_actived_at": "2019-09-21T08:09:06.000000Z"
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
                "count": 9,
                "created_at": "2019-12-03 18:47:39",
                "updated_at": "2019-12-05 10:53:34"
            },
            {
                "id": 8,
                "title": "测试标题00",
                "content": "测试内容00",
                "image": [
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                ],
                "user_id": 1,
                "category_id": 2,
                "answer_count": 2,
                "user": {
                    "id": 1,
                    "tx_id": null,
                    "accid": "yx_1",
                    "name": "王大力",
                    "avatar": "",
                    "description": null,
                    "level": 0
                },
                "answer": {
                    "id": 9,
                    "question_id": 8,
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
                    "content": "测试回答123456",
                    "image": [
                        "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                    ],
                    "reply_count": 0,
                    "praise_count": 0,
                    "created_at": "2019-12-07 10:05:25",
                    "updated_at": "2019-12-07 10:05:25"
                },
                "count": 0,
                "created_at": "2019-12-04 09:57:39",
                "updated_at": "2019-12-09 10:50:42"
            },
            {
                "id": 9,
                "title": "测试标题123456",
                "content": "测试内容123456",
                "image": [
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                ],
                "user_id": 2,
                "category_id": 3,
                "answer_count": 2,
                "user": {
                    "id": 2,
                    "tx_id": null,
                    "accid": "yx_2",
                    "name": "刘铁柱",
                    "avatar": "",
                    "description": null,
                    "level": 0
                },
                "answer": {
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
                        "last_actived_at": "2019-09-21T08:09:06.000000Z"
                    },
                    "content": "测试回答123456",
                    "image": [
                        "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                    ],
                    "reply_count": 1,
                    "praise_count": 0,
                    "created_at": "2019-12-09 14:08:24",
                    "updated_at": "2019-12-09 14:09:01"
                },
                "count": 2,
                "created_at": "2019-12-07 09:35:18",
                "updated_at": "2019-12-09 14:21:55"
            },
            {
                "id": 2,
                "title": "测试标题",
                "content": "测试内容",
                "image": [
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                ],
                "user_id": 1,
                "category_id": 1,
                "answer_count": 0,
                "user": {
                    "id": 1,
                    "tx_id": null,
                    "accid": "yx_1",
                    "name": "王大力",
                    "avatar": "",
                    "description": null,
                    "level": 0
                },
                "answer": null,
                "count": 0,
                "created_at": "2019-12-04 09:11:39",
                "updated_at": "2019-12-04 09:11:39"
            },
            {
                "id": 3,
                "title": "测试标题88",
                "content": "测试内容88",
                "image": [
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                ],
                "user_id": 1,
                "category_id": 8,
                "answer_count": 0,
                "user": {
                    "id": 1,
                    "tx_id": null,
                    "accid": "yx_1",
                    "name": "王大力",
                    "avatar": "",
                    "description": null,
                    "level": 0
                },
                "answer": null,
                "count": 0,
                "created_at": "2019-12-04 09:25:27",
                "updated_at": "2019-12-04 09:25:27"
            },
            {
                "id": 7,
                "title": "测试标题99",
                "content": "测试内容99",
                "image": [
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                    "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                ],
                "user_id": 1,
                "category_id": 5,
                "answer_count": 0,
                "user": {
                    "id": 1,
                    "tx_id": null,
                    "accid": "yx_1",
                    "name": "王大力",
                    "avatar": "",
                    "description": null,
                    "level": 0
                },
                "answer": null,
                "count": 0,
                "created_at": "2019-12-04 09:36:37",
                "updated_at": "2019-12-04 09:36:37"
            }
        ],
        "links": {
            "first": "http://tongxun.test/api/question/recommend?page=1",
            "last": "http://tongxun.test/api/question/recommend?page=1",
            "prev": null,
            "next": null
        },
        "meta": {
            "current_page": 1,
            "from": 1,
            "last_page": 1,
            "path": "http://tongxun.test/api/question/recommend",
            "per_page": 10,
            "to": 6,
            "total": 6
        },
        "ok": 1
}
```

