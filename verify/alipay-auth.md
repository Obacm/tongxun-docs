# 支付宝登陆授权

用户绑定支付宝

## 请求地址

> `verify/info`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应示例

```json
{
    "data": {
        "info_str": "apiname=com.alipay.account.auth&app_id=2019102568589740&app_name=mc&method=alipay.open.auth.sdk.code.get&auth_type=AUTHACCOUNT&biz_type=openservice&pid=2088631610069015&product_id=APP_FAST_LOGIN&scope=kuaijie&target_id=y201910281631387437&sign_type=RSA2&sign=dVt2t7SWyc2NYyXm2aEU2zZNFWYEJSCidBqn1DrcsL7+45wMPOf9fKtwa1vvFhD91/iyg6sanQjqshuRm8CYAn2XZTbXLGJIui4/ip1RfOAD1I55ofXvFmteeJQ4TX2DBZibPYFf6w6B7Iyj/EEnpdBcnmhfAmGbGt3oohR8IzHtX4OvBEGC1vlOP+GLGdbFjmVqU7EWrf7c92ey2Izal59IvDD1QVGfcHb5lzwsn5UlccTyLAqfkos+fGcl2tBun7n5oFCZK3YH/G3rWHKC73MeyzcFzRdBlElnX0berDCv/n+Tt6EYf/i1FZIi4ZFdIxuvBMmrWP9UGPSteGuKHw=="
    },
    "ok": 1
}
```

