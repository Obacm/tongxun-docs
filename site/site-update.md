# 地址更新

用户更新一个地址

## 请求地址

> `sites/[id]`

##### <font color="blue">须知</font>

> {warning} [id] 表示地址ID 需要把地址ID 拼接在 `sites/` 后面

## 请求类型

> `PATCH`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

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
    "ok": 1
}
```

