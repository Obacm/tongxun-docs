# 钱包支付

钱包支付

## 请求地址

> `trade/payment`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `order_no` `string` 订单号
> - `pay_password` `string` 支付密码

## 响应示例

```json
{
    "ok": 1
}
```

## 异常响应示例

```json
{
    "msg": "订单不存在",
    "ok": 0
}
```

```json
{
    "msg": "不属于自己的订单",
    "ok": 0
}
```

```json
{
    "msg": "订单已过期",
    "ok": 0
}
```

```json
{
    "msg": "支付密码错误",
    "ok": 0
}
```

```json
{
    "msg": "余额不足",
    "ok": 0
}
```

```json
{
    "msg": "支付失败",
    "ok": 0
}
```