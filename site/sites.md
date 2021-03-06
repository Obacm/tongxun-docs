# 地址列表

获取用户已有的地址列表

## 请求地址

> `sites`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应参数

> - `id` `int` 地址ID
> - `longitude` `float` 经度
> - `latitude` `float` 纬度
> - `address` `string` 地址
> - `village` `string` 详情
> - `citycode` `string` 城市码
> - `cityname` `string` 城市名
> - `is_default` `bool` 是否默认

## 响应示例

```json
{
    "data": [
        {
            "id": 1,
            "longitude": 104.07642,
            "latitude": 38.6518,
            "address": "辽宁省大连市甘井子区",
            "village": "西关街38-205",
            "citycode": "0411",
            "cityname": "大连市",
            "is_default": true
        },
        {
            "id": 2,
            "longitude": 104.07642,
            "latitude": 38.6518,
            "address": "辽宁省大连市甘井子区",
            "village": "西关街38-205",
            "citycode": "0411",
            "cityname": "大连市",
            "is_default": false
        }
    ],
    "ok": 1
}
```

