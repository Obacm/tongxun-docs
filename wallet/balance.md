# 余额

获取余额

## 请求地址

> `wallet/balance`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应参数

> - `balance` `string` 余额

## 响应示例

```json
{
    "data": {
        "balance": "180.00",
        "status": 1,
        "has_freezed": false
    },
    "ok": 1
}
```

