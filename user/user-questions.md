# 获取他的问题

获取一个用户信息

## 请求地址

> `user/[id]/questions`

##### <font color="blue">须知</font>

> {warning} [id] 表示用户ID 需要把用户ID 拼接在 `users/` 后面

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应示例

```json
{
    "data": [
            {
                "id": 4,
                "title": "家里卫生间贴瓷砖",
                "content": "需要一个瓦工",
                "answer_count": 0,
                "created_at": "2019-12-21 10:18:03"
            },
            {
                "id": 1,
                "title": "测试标题1",
                "content": "测试内容1",
                "answer_count": 1,
                "created_at": "2019-12-13 10:25:11"
            }
        ],
        "links": {
            "first": "http://tongxun.test/api/user/1/questions?page=1",
            "last": "http://tongxun.test/api/user/1/questions?page=1",
            "prev": null,
            "next": null
        },
        "meta": {
            "current_page": 1,
            "from": 1,
            "last_page": 1,
            "path": "http://tongxun.test/api/user/1/questions",
            "per_page": 15,
            "to": 2,
            "total": 2
        },
        "ok": 1
}
```