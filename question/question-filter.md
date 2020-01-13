# 问题搜索

问题搜索

## 请求地址

> `questions/filter`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Query

> - `keyword` `string` 搜索内容

```json
{
   "data": [
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
                   "last_actived_at": "2019-12-23T07:25:05.000000Z"
               },
               "category_id": 3,
               "answer_count": 1,
               "created_at": "2019-12-13 10:25:11",
               "updated_at": "2019-12-23 15:25:39"
           },
           {
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
                   "last_actived_at": "2019-12-23T07:25:38.000000Z"
               },
               "category_id": 6,
               "answer_count": 1,
               "created_at": "2019-12-13 10:26:11",
               "updated_at": "2019-12-13 10:28:23"
           },
           {
               "id": 3,
               "title": "测试标题3",
               "content": "测试内容3",
               "image": [
                   "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
                   "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
               ],
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
               "category_id": 5,
               "answer_count": 1,
               "created_at": "2019-12-13 10:26:52",
               "updated_at": "2019-12-13 10:30:31"
           }
       ],
       "ok": 1
}
```