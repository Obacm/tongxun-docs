# 红包创建

红包创建

## 请求地址

> `packets`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `title` `string` 红包祝语
> - `type` `int` 红包所属类型 `0: 人, 1: 群`
> - `count` `int` 个数 `群红包必传`
> - `amount` `float` 金额
> - `to_accid` `string` 接收者 `人/群 云信accid`
> - `order_no` `string` 红包订单号
> - `subject` `string` 描述 `人昵称，群名称`
> - `pay_password` `string` 支付密码

## 响应示例

```json
{
    "ok": 1
}
```