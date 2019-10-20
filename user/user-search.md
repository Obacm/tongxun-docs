# 查询用户

根据手机号码查询一个用户

## 请求地址

> `users/search`

## 请求类型

> `GET`

## 请求参数

#### Query

> - `mobile` `string` 手机号码

## 响应示例

```json
{
    "data": {
        "id": 1,
        "tx_id": "tx_7640aedcb77b",
        "accid": "yx_1",
        "name": "tx_7640aedcb77b",
        "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
        "description": "",
        "level": 0,
        "privacies": {
            "qa_enabled": false,
            "task_enabled": false,
            "email_enabled": false,
            "gender_enabled": false,
            "mobile_enabled": false,
            "address_enabled": false
        },
        "has_idcard_verified": false,
        "has_payee_verified": false,
        "active_at": "",
        "login_at": "2019-10-14 11:19:00"
    },
    "ok": 1
}
```

## 异常示例

> - `用户不存在`

```json
{
    "msg": "用户不存在",
    "ok": 0
}
```