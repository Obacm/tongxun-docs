# 获取他的问题

获取一个用户信息

## 请求地址

> `user/[id]/questions`

##### <font color="blue">须知</font>

> {warning} [id] 表示用户ID 需要把用户ID 拼接在 `users/` 后面

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
                    "last_actived_at": "2019-12-23T10:41:50.000000Z"
                },
                "category_id": 6,
                "answer_count": 0,
                "created_at": "2019-12-21 10:18:03",
                "updated_at": "2019-12-21 10:18:03"
            },
            {
                "id": 1,
                "title": "测试标题1",
                "content": "测试内容1",
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
                    "last_actived_at": "2019-12-23T10:41:50.000000Z"
                },
                "category_id": 3,
                "answer_count": 1,
                "created_at": "2019-12-13 10:25:11",
                "updated_at": "2019-12-23 15:25:39"
            }
        ],
        "links": {
            "first": "http://tongxun.test/api/user/1/questions?page=1",
            "last": "http://tongxun.test/api/user/1/questions?page=1",
            "prev": null,
            "next": null
        },
        "meta": {
            "current_page": 1,
            "from": 1,
            "last_page": 1,
            "path": "http://tongxun.test/api/user/1/questions",
            "per_page": 15,
            "to": 2,
            "total": 2
        },
        "ok": 1
}
```