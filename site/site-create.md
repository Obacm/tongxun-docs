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

> - `longitude` `float` 经度
> - `latitude` `float` 纬度
> - `realname` `string` 姓名
> - `address` `string` 地址
> - `mobile` `string` 手机
> - `village` `string` 详情
> - `default` `bool` 是否默认

## 响应示例

```json
{
    "ok": 1
}
```

