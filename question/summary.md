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
             "title": "测试标题1",
             "content": "测试内容1",
             "image": [
                 "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                 "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
             ],
             "user_id": 1,
             "category_id": 3,
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
             "answer": [
                 {
                     "id": 1,
                     "question_id": 1,
                     "user": {
                         "id": 3,
                         "name": "奥里给",
                         "mobile": "15898146123",
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
                         "accid": "yx_3",
                         "has_idcard_verified": false,
                         "has_payee_verified": false,
                         "has_pay_password": false,
                         "last_actived_at": "2019-12-09T06:23:32.000000Z"
                     },
                     "content": "测试回答123456",
                     "image": [
                         "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
                     ],
                     "reply_count": 2,
                     "praise_count": 2,
                     "comment": [
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
                         },
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
                                 "last_actived_at": "2019-12-20T02:42:10.000000Z"
                             },
                             "content": "测试评论888",
                             "praise_count": 0,
                             "created_at": "2019-12-18 15:49:22",
                             "updated_at": "2019-12-18 15:49:22"
                         }
                     ],
                     "created_at": "2019-12-13 10:27:26",
                     "updated_at": "2019-12-20 10:42:10"
                 },
                 {
                     "id": 4,
                     "question_id": 1,
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
                     "reply_count": 1,
                     "praise_count": 0,
                     "comment": [
                         {
                             "id": 5,
                             "answer_id": 4,
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
                                 "last_actived_at": "2019-12-20T02:42:10.000000Z"
                             },
                             "content": "测试评论666",
                             "praise_count": 0,
                             "created_at": "2019-12-18 15:54:22",
                             "updated_at": "2019-12-18 15:54:22"
                         }
                     ],
                     "created_at": "2019-12-13 13:52:22",
                     "updated_at": "2019-12-18 15:54:22"
                 }
             ],
             "count": 3,
             "created_at": "2019-12-13 10:25:11",
             "updated_at": "2019-12-13 13:52:22"
         },
         "ok": 1
}
```

