# 发布回答

回答一个问题

## 请求地址

> `answer/store`

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
           "id": 9,
           "question_id": 6,
           "user_id": 1,
           "content": "测试回答 哈哈",
           "image": [
               "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
           ],
           "reply_count": 0,
           "praise_count": 0,
           "created_at": "2019-12-05 10:59:27",
           "updated_at": "2019-12-05 10:59:27"
       },
       "ok": 1
}
```