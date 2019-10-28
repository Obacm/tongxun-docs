# 实名认证

用户绑定身份证

## 请求地址

> `verify/person`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `realname` `string` 真实姓名
> - `idcard` `string` 身份证号

## 响应示例

```json
{
    "ok": 1
}
```

