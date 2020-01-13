# 分类列表

获取分类列表

## 请求地址

> `question/[id]`

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
            }
        ],
        "links": {
            "first": "http://tongxun.test/api/question/6/show?page=1",
            "last": "http://tongxun.test/api/question/6/show?page=1",
            "prev": null,
            "next": null
        },
        "meta": {
            "current_page": 1,
            "from": 1,
            "last_page": 1,
            "path": "http://tongxun.test/api/question/6/show",
            "per_page": 10,
            "to": 1,
            "total": 1
        },
        "ok": 1
}
```

