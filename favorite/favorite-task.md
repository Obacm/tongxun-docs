# 任务收藏与取消

任务的收藏、任务的取消收藏

## 请求地址

> `favorite/tasks/[id]`

##### <font color="blue">须知</font>

> {warning} [id] 表示任务ID 需要把任务ID 拼接在 `tasks/` 后面

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