# 问题详情

问题详情

## 请求地址

> `questions/[id]`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

```json
{
     "data": {
            "id": 9,
            "title": "测试标题123456",
            "content": "测试内容123456",
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
            "category_id": 3,
            "answer_count": 2,
            "created_at": "2019-12-07 09:35:18",
            "updated_at": "2019-12-09 14:21:55"
        },
        "ok": 1
}
```