# 推荐列表

问题综合详情

## 请求地址

> `question/[id]/summary`

## 请求类型

> `GET`

## 请求参数

## 响应示例

```json
{
     "data": {
             "id": 1,
             "title": "家里卫生间贴瓷砖",
             "content": "需要一个瓦工",
             "image": [
                 "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                 "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
             ],
             "user_id": 1,
             "category_id": 6,
             "answer_count": 1,
             "user": {
                 "id": 1,
                 "tx_id": null,
                 "accid": "yx_1",
                 "name": "王大力",
                 "avatar": "",
                 "description": null,
                 "level": 0
             },
             "answer": [
                 {
                     "id": 1,
                     "question_id": 1,
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
                         "last_actived_at": "2020-01-06T06:54:22.000000Z"
                     },
                     "content": "测试回答123456",
                     "image": [],
                     "reply_count": 2,
                     "praise_count": 5,
                     "question": {
                         "id": 1,
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
                             "last_actived_at": "2020-01-06T06:54:22.000000Z"
                         },
                         "category_id": 6,
                         "answer_count": 1,
                         "created_at": "2020-01-03 16:20:29",
                         "updated_at": "2020-01-03 16:21:46"
                     },
                     "comment": [
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
                                 "last_actived_at": "2020-01-06T06:54:22.000000Z"
                             },
                             "content": "测试评论666",
                             "praise_count": 13,
                             "has_praised": false,
                             "created_at": "2020-01-03 16:24:38",
                             "updated_at": "2020-01-06 14:35:55"
                         }
                     ],
                     "has_liked": false,
                     "created_at": "2020-01-03 16:21:46",
                     "updated_at": "2020-01-06 14:36:01"
                 }
             ],
             "count": 1,
             "created_at": "2020-01-03 16:20:29",
             "updated_at": "2020-01-03 16:21:46"
         },
         "ok": 1
}
```

