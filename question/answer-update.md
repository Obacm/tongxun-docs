# 编辑回答

用户编辑自己回答的一个问题

## 请求地址

> `answer/[id]/update`

## 请求类型

> `PATCH`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `content` `string` 内容
> - `image` `array` 图片

## 响应示例

```json
{
    "ok": 1
}
```

