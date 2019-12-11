# 申请人任务完成

申请人提交完成任务申请

## 请求地址

> `task/[id]/complete`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `evidences` `array` 图片 `必填`
> - `score` `int` 评分
> - `tags` `array` `标签` 标签

## 响应示例

```json
{
    "ok": 1
}
```
