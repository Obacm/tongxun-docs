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

> - `auth_code` `string` 授权码

## 响应示例

```json
{
    "ok": 1
}
```

## 异常示例

> - `授权失败`

```json
{
    "msg": "授权失败",
    "ok": 0
}
```
