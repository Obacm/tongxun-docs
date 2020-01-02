# 评论点赞

给一条评论点赞

## 请求地址

> `praise/store`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `comment_id` `int` 评论id

```json
{
   "data": {
        "id": 2,
        "comment_id": "1",
        "user_id": 1,
        "state": 1,
        "created_at": "2020-01-02 14:48:13",
        "updated_at": "2020-01-02 14:48:13"
    },
    "ok": 1
}
```