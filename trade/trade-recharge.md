# 充值

根据订单号进行充值

## 请求地址

> `trade/recharge`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `gateway` `string` 支付渠道 `alipay: 支付宝`
> - `order_no` `string` 订单号

## 响应示例

```json
{
    "data": {
        "order_str": "alipay_sdk=lokielse%2Fomnipay-alipay&app_id=2019102568589740&biz_content=%7B%22subject%22%3A%22%5Cu5145%5Cu503c%22%2C%22body%22%3A%22%5Cu94b1%5Cu5305%5Cu5145%5Cu503c%22%2C%22out_trade_no%22%3A%2220191115142845464867%22%2C%22total_amount%22%3A%22100.00%22%2C%22product_code%22%3A%22QUICK_MSECURITY_PAY%22%7D&charset=UTF-8&format=JSON&method=alipay.trade.app.pay&notify_url=https%3A%2F%2Fapi.wtdoe.com%2Fapi%2Ftrade%2Fnotify%2Falipay&sign_type=RSA2&timestamp=2019-11-15+14%3A29%3A17&version=1.0&sign=HbjfYKAVx%2F65yScOmpZDehCJFuapUvDM6zstqxwn9ejT1kkfdsSxhBZlzDAyEr9Vc7vUhp0Sjko2OfIKPahCtnVStIGredjmPxVENmaLaIajv1O7JQ3edANHl5QCgaIzmg7LpCzOTvtcyumCZ9FHG8LsA%2BLz0BR53VoLcUKFjIkCvR891jY0fZVkZsqeLfNyaWmNVw9wUktK6c1o6H7BX2jdHK%2FzCkpHDedyuvN5kZRtlUNFmwYo6%2FWY8FajKzeesycEr%2Bl3n1n0igO75VaQ8rj94FwHvc0hNh3byoUvAD2rbYO9amFoQf4uMOu2sK5EPxkbtoaY1H%2FGypHByJSw4w%3D%3D"
    },
    "ok": 1
}
```