# 问题发布

创建一个问题

## 请求地址

> `question/store`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `title` `string` 标题
> - `content` `string` 内容
> - `image` `array` 图片
> - `category_id` `int` 图片

```json
{
   "data": {
        "id": 3,
        "title": "测试标题",
        "content": "测试内容",
        "image": [
            "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
            "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg",
            "https://tvax3.sinaimg.cn/crop.0.0.1006.1006.180/4c7f9b17ly8fwpigg780qj20ry0ryabc.jpg"
        ],
        "user_id": 1,
        "category_id": "1",
        "answer_count": null,
        "created_at": "2019-11-27 16:56:47",
        "updated_at": "2019-11-27 16:56:47"
    },
    "ok": 1
}
```