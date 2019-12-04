# 广告获取

所有位置的广告获取

## 请求地址

> `complex/version`

## 请求类型

> `GET`

## 请求参数

#### Query

> - `client` `int` 客户端类型 `1: ios，2: android`
> - `app` `string` app类型 `master: 主要发布版本`
> - `version` `string` 本地app版本号

## 响应示例

```json
{
    "data": {
        "client": 2,
        "app": "master",
        "version": "2.5",
        "content": "增加任务倒计时",
        "link": "https://api.wtdoe.com/docs/master/advert/ad",
        "environment": "production",
        "is_force": true
    },
    "ok": 1
}
```

```json
{
    "msg": "已是最新版本",
    "ok": 0
}
```
