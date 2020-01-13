# 发布评论

评论一个回答

## 请求地址

> `comments`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `content` `string` 内容
> - `question_id` `int` 问题id

```json
{
   "data": {
           "id": 16,
           "answer_id": "12",
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
               "last_actived_at": "2019-12-11T07:09:39.000000Z"
           },
           "content": "测试评论52",
           "praise_count": 0,
           "created_at": "2019-12-11 15:09:39",
           "updated_at": "2019-12-11 15:09:39"
       },
       "ok": 1
}
```