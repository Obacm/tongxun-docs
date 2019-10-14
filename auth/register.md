# 用户注册

为应用增加用户

## 请求地址

> `auth/register`

## 请求类型

> `POST`

## 请求参数

#### Body

> - `mobile` 手机号码
> - `password` 密码
> - `password_confirmation` 密码确认

## 响应示例

```json
{
    "ok": 1
}
```

## 异常示例

> - `手机 已经存在`
> - `密码 两次输入不一致`
> - `密码 至少为 6 个字符`

```json
{
    "msg": "手机 已经存在",
    "ok": 0
}
```