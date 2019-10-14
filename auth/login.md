# 用户登陆

通过账号和密码登陆应用

## 请求地址

> `auth/login`

## 请求类型

> `POST`

## 请求参数

#### Body

> - `mobile` 手机号码
> - `password` 密码

## 响应示例

```json
{
    "data": {
        "access_token": "eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiIsImp0aSI6IjhjYTM1Yzc4YzEyOGRmOTk0MTEyMDNlMWRmNWI0YWU3N2UzNjlmOTVkZDMyZmIyMjg0OWRhNGMxOTY4OTU3ZGQwYjJiMGQ4MTIxYTA3YTMwIn0.eyJhdWQiOiIxIiwianRpIjoiOGNhMzVjNzhjMTI4ZGY5OTQxMTIwM2UxZGY1YjRhZTc3ZTM2OWY5NWRkMzJmYjIyODQ5ZGE0YzE5Njg5NTdkZDBiMmIwZDgxMjFhMDdhMzAiLCJpYXQiOjE1NzEwMTU3NTYsIm5iZiI6MTU3MTAxNTc1NiwiZXhwIjoxNjAyNjM4MTU2LCJzdWIiOiIyIiwic2NvcGVzIjpbXX0.GM79SvURY-BfcaYIeTBAt_y7QM-lx2JUkSZkU6-41PdnMm9cnSIcVqn5tgssTetptU_QaA7dDsBvGSzxqC54pb-0RNwymc3jbLFEAUvxeGzSfQs2u93hOhe4YhhnJ0LuN8VfOIKoVOFwqxm8vWGXzynMLFdytGsoFU6KsMwi1BPDodtvKvMAcKZu8ZxblmNPrT5P1gRwnN5USOagN9lzkQ16s8gg7k40L7Z-pB_2AP-QsX7V_3DFLlbdXb0TZVpliPaqQE0w89DSTdZ4PMPLTNbjH6KvkAW24nfCJu8YcCf_ef7TPY2S3Y12eYP5MEDZFlD10a-XFo4St3kNM2lfha2DAR-zI4zRQ3BOW2WC85x-XnA77wnCnn2QzLGtWAy7_VlNR7O12v_Y7FpU0TREc5GfoQBRVkj2pyfH0uRQtPt2-LnJY5VnEbNbbFQtYxsHCUjEFQaxPQ49Bys0-z9kO-f-jSsBirycODez3KAipa2aGKAQq1Lw0o8z24u4S-_deQpqkpFRCSkO3iKTTQhVHNauME6Bay0KgNfTlb31prd2nrDghOxLYIkFexvF_Tj8g4MV4sPd8x213Pb4figZo-ZFryUX2coHESTj-LeZCg-UbTQ0TSTS4ta9eRExY5OMYlNMDNGIR8MnPWYnCkkB_L3PHrPy7KGUbL7kBNyjnlE"
    },
    "ok": 1
}
```

## 异常示例

> - `用户名或密码错误`

```json
{
    "msg": "用户名或密码错误",
    "ok": 0
}
```