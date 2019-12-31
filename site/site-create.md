# 地址创建

用户创建一个地址

## 请求地址

> `sites`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `longitude` `string` 经度
> - `latitude` `string` 纬度
> - `address` `string` 地址
> - `village` `string` 详情
> - `citycode` `string` 城市码
> - `cityname` `string` 城市名
> - `is_default` `bool` 是否默认

## 响应示例

```json
{
    "ok": 1
}
```

