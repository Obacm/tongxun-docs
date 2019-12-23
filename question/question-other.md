# 他人问题

他人问题

## 请求地址

> `question/user/[id]/show`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

```json
{
     "data": [
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
         "links": {
             "first": "http://tongxun.test/api/question/user/3/other?page=1",
             "last": "http://tongxun.test/api/question/user/3/other?page=1",
             "prev": null,
             "next": null
         },
         "meta": {
             "current_page": 1,
             "from": 1,
             "last_page": 1,
             "path": "http://tongxun.test/api/question/user/3/other",
             "per_page": 10,
             "to": 1,
             "total": 1
         },
         "ok": 1
}
```