# 提现

提现到第三方应用

## 请求地址

> `trade/withdraw`

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