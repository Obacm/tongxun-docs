# 回答点赞

给一条回答点赞

## 请求地址

> `like/store`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `answer_id` `int` 回答id

```json
{
   "data": {
        "id": 1,
        "answer_id": "1",
        "user_id": 1,
        "state": 1,
        "created_at": "2020-01-02 14:51:03",
        "updated_at": "2020-01-02 14:51:03"
    },
    "ok": 1
}
```