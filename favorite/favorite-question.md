# 问题收藏与取消

问题的收藏、问题的取消收藏

## 请求地址

> `favorite/questions/[id]`

##### <font color="blue">须知</font>

> {warning} [id] 表示问题ID 需要把问题ID 拼接在 `questions/` 后面

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应示例

```json
{
    "ok": 1
}
```