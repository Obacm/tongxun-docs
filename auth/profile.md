# 获取已登陆的用户

获取已登陆的用户信息

## 请求地址

> `auth/profile`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应参数

> - `id` `int` 用户ID
> - `tx_id` `string` 同讯ID
> - `accid` `string` 云信ID
> - `name` `string` 用户昵称
> - `mobile` `string` 手机号
> - `avatar` `string` 头像
> - `description` `string` 个性签名
> - `gender` `string` 性别
> - `birthday` `string` 生日
> - `province` `string` 省
> - `city` `string` 市
> - `level` `int` 用户等级
> - `privacies` `json` 用户隐私
> - `has_idcard_verified` `bool` 身份认证
> - `has_payee_verified` `bool` 支付宝认证
> - `active_at` `string` 最近活动时间
> - `login_at` `string` 登陆时间

## 响应示例

```json
{
    "data": {
        "id": 1,
        "tx_id": "7640aedcb77b",
        "accid": "yx_1",
        "name": "7640aedcb77b",
        "mobile": "15140569062",
        "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
        "description": "",
        "gender": "male",
        "birthday": "",
        "province": "",
        "city": "",
        "level": 0,
        "privacies": {
            "qa_enabled": true,
            "task_enabled": true,
            "email_enabled": false,
            "gender_enabled": false,
            "mobile_enabled": false,
            "address_enabled": false
        },
        "has_idcard_verified": false,
        "has_payee_verified": false,
        "active_at": "",
        "login_at": "2019-10-14 09:44:58"
    },
    "ok": 1
}
```