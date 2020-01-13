# 编辑问题

用户编辑自己提问的一个问题

## 请求地址

> `questions/[id]`

## 请求类型

> `PATCH`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `title` `string` 标题
> - `content` `string` 内容
> - `category_id` `int` 问题类型
> - `image` `array` 图片

## 响应示例

```json
{
    "ok": 1
}
```

