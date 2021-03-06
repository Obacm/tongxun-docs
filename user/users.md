# 获取用户信息

获取一个用户信息

## 请求地址

> `users/[id]`

##### <font color="blue">须知</font>

> {warning} [id] 表示用户ID 需要把用户ID 拼接在 `users/` 后面

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
> - `avatar` `string` 头像
> - `bio` `string` 个性签名
> - `gender` `string` 性别
> - `birthday` `string` 生日
> - `province` `string` 省
> - `city` `string` 市
> - `level` `int` 用户等级
> - `score` `string` 评分
> - `mobile` `string` 手机号
> - `privacies` `json` 用户隐私
> - `has_idcard_verified` `bool` 身份认证
> - `has_payee_verified` `bool` 支付宝认证
> - `last_actived_at` `string` 最近活跃时间

## 响应示例

```json
{
    "data": {
        "id": 1,
        "tx_id": "7640aedcb77b",
        "accid": "yx_1",
        "name": "7640aedcb77b",
        "avatar": "http://api.tongxun.test/storage/default_avatars/pic_020.jpg",
        "bio": "",
        "level": 0,
        "score": "5.0",
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
        "last_actived_at": "一个月前活跃" 
    },
    "ok": 1
}
```