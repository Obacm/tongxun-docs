# 问题详情

问题详情

## 请求地址

> `question/[id]/show`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

```json
{
    "data": {
        "id": 2,
        "title": "测试标题2",
        "content": "测试内容2",
        "image": [
            "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
            "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
        ],
        "user_id": 1,
        "category_id": 2,
        "answer_count": null,
        "created_at": "2019-11-29 10:48:08",
        "updated_at": "2019-11-29 10:48:08"
    },
    "ok": 1
}
```