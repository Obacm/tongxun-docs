# 任务保存草稿

创建云端任务保存

## 请求地址

> `task/store`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `id` `int` 任务ID `可选参数，存在: 更新当前任务信息，不存在: 新增草稿`
> - `title` `string` 标题
> - `hire_amount` `decimal` 佣金
> - `fee_amount` `decimal` 赏金
> - `node` `int` 一级分类
> - `mode` `int` 二级分类
> - `site_id` `int` 地址ID
> - `description` `string` 描述
> - `pics` `array` 图片
> - `start_at` `string` 开始时间
> - `end_at` `string` 结束时间

## 响应示例

```json
{
    "ok": 1
}
```