# 问题发布

创建一个问题

## 请求地址

> `questions`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `title` `string` 标题
> - `content` `string` 内容
> - `image` `array` 图片
> - `category_id` `int` 问题类型

```json
{
   "data": {
           "id": 10,
           "title": "测试标题123456",
           "content": "测试内容123456",
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
               "last_actived_at": "2019-12-11T07:21:47.000000Z"
           },
           "category_id": 3,
           "answer_count": 0,
           "created_at": "2019-12-11 15:21:47",
           "updated_at": "2019-12-11 15:21:47"
       },
       "ok": 1
}
```