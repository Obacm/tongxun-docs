# 任务发布

创建一个有效的任务

## 请求地址

> `task/publish`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `id` `int` 任务ID `可选参数，存在: 更新当前任务信息并发布，不存在: 发布新的任务`
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

> - `order_no` `string` 订单号
> - `actual_amount` `string` 实际支付金额
> - `channel` `string` 支付类型

#### 有赏金任务

```json
{
    "data": {
        "id": 26,
        "order_no": "20191127143455345196",
        "amount": "40.00",
        "currency": "CNY",
        "type": 3,
        "subject": "任务赏金",
        "body": "",
        "actual_amount": "40.00",
        "channel": "wallet",
        "state": 0,
        "orderable_id": 40,
        "orderable_type": "task",
        "succeed_at": "",
        "canceled_at": "",
        "created_at": "2019-11-27 14:34:55",
        "has_succeed": false,
        "has_expired": false,
        "has_canceled": false,
        "has_refunded": false
    },
    "ok": 1
}
```

#### 无任务

```json
{
    "ok": 1
}
```