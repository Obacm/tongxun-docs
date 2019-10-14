# 编辑用户标签

获取标签列表

## 请求地址

> `tags/edit`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应参数

> - `id` 标签ID
> - `name` 标签
> - `type` 标签类型 ` 1: 身份 2: 工种`
> - `selected` 是否已选择

## 响应示例

```json
{
    "data": {
        "1": [
            {
                "id": 1,
                "name": "全职",
                "type": "1",
                "selected": true
            }
        ],
        "2": [
            {
                "id": 2,
                "name": "服务员",
                "type": "2",
                "selected": true
            }
        ]
    },
    "ok": 1
}
```