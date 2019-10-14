# 获取用户信息

获取一个用户信息

## 请求地址

> `users/[id]`

##### <font color="yellow">须知</font>

> {warning} [id] 表示用户ID 需要把用户ID 拼接在 `users/` 后面

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应参数

> - `id` 用户ID
> - `tx_id` 同讯ID
> - `accid` 云信ID
> - `name` 用户昵称
> - `avatar` 头像
> - `gender` 性别
> - `birthday` 生日
> - `province` 省
> - `city` 市
> - `level` 用户等级
> - `mobile` 手机号
> - `tags` 用户标签
> - `privacies` 用户隐私
> - `has_idcard_verified` 身份认证
> - `has_payee_verified` 支付宝认证
> - `active_at` 最近活动时间
> - `login_at` 登陆时间

## 响应示例

```json
{
    "data": {
        "id": 1,
        "tx_id": "tx_7640aedcb77b",
        "accid": "yx_1",
        "name": "tx_7640aedcb77b",
        "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
        "level": 0,
        "tags": [
            {
                "id": 1,
                "name": "全职",
                "type": 1
            },
            {
                "id": 2,
                "name": "服务员",
                "type": 2
            }
        ],
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