# 发布回答

回答一个问题

## 请求地址

> `answers`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `content` `string` 内容
> - `image` `array` 图片
> - `question_id` `int` 问题id

```json
{
   "data": {
           "id": 14,
           "question_id": 10,
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
               "last_actived_at": "2019-12-11T07:32:16.000000Z"
           },
           "content": "测试回答123456",
           "image": [
               "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
           ],
           "reply_count": 0,
           "praise_count": 0,
           "created_at": "2019-12-11 15:32:17",
           "updated_at": "2019-12-11 15:32:17"
       },
       "ok": 1
}
```