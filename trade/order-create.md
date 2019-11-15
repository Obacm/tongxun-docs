# 订单创建

创建订单

## 请求地址

> `trade/orders`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `amount` `string` 金额
> - `subject` `string` 描述
> - `channel` `string` 支付渠道
> - `type` `string` 订单类型

## 响应示例

```json
{
    "data": {
        "id": 1,
        "order_no": "20191115142845464867",
        "amount": "100.00",
        "currency": "CNY",
        "client_ip": "123.185.181.21",
        "type": 1,
        "subject": "充值",
        "body": "",
        "actual_amount": "100.00",
        "channel": "alipay",
        "status": 0,
        "orderable_id": "",
        "orderable_type": "",
        "paid_at": "",
        "succeed_at": "",
        "canceled_at": "",
        "created_at": "2019-11-15 14:28:45",
        "has_paid": false,
        "has_succeed": false,
        "has_canceled": false
    },
    "ok": 1
}
```