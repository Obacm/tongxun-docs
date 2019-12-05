# 回答详情

回答详情

## 请求地址

> `answer/[id]/show`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

```json
{
    "data": {
            "id": 1,
            "question_id": 1,
            "user_id": 1,
            "content": "测试内容88",
            "image": [
                "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
            ],
            "reply_count": 0,
            "praise_count": 0,
            "created_at": "2019-12-05 10:37:07",
            "updated_at": "2019-12-05 14:19:10"
        },
        "ok": 1
}
```