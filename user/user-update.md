# 更新用户信息

更新一个用户信息

## 请求地址

> `users/[id]`

##### <font color="blue">须知</font>

> {warning} [id] 表示用户ID 需要把用户ID 拼接在 `users/` 后面

## 请求类型

> `PATCH`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `name` `string` 用户昵称
> - `avatar` `string` 头像
> - `description` `string` 个性签名
> - `gender` `string` 性别
> - `birthday` `string` 生日
> - `province` `string` 省
> - `city` `string` 市

##### <font color="red">提示</font>

> :open_hands: 以上参数皆是可选

## 响应示例

```json
{
    "data": {
        "id": 1,
        "tx_id": "f3d0d305f962",
        "accid": "yx_1",
        "name": "obacmsss",
        "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
        "description": "",
        "gender": "male",
        "birthday": "",
        "province": "",
        "city": "",
        "level": 0,
        "privacies": {
            "qa_enabled": false,
            "task_enabled": false,
            "email_enabled": false,
            "gender_enabled": true,
            "mobile_enabled": true,
            "address_enabled": true
        },
        "has_idcard_verified": true,
        "has_payee_verified": true,
        "active_at": "",
        "login_at": "2019-10-30 14:55:55"
    },
    "ok": 1
}
```