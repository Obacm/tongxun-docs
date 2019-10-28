# 支付宝认证

用户绑定支付宝

## 请求地址

> `verify/alipay`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `payee_id` `string` 支付宝ID
> - `payee_name` `string` 支付宝昵称

## 响应示例

```json
{
    "ok": 1
}
```

