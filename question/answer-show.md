# 回答详情

回答详情

## 请求地址

> `answers/[id]`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

```json
{
     "data": {
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
        "ok": 1
}
```