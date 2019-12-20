# 客服

聊天框里任务分享

## 请求地址

> `task/[id]/customer`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应示例

```json
{
    "ok": 1
}
```
## 客服云信accid
`yx_003`

## 云信消息

```json
{
    "type": 209,
    "body": {
        "title": "上门修电脑",
        "hire_amount": "20.00",
        "fee_amount": "30.00",
        "description": "电脑开不开机，黑屏",
        "user": {
            "id": 1,
            "tx_id": "f3d0d305f962",
            "name": "obacmss",
            "avatar": "http:://api.tongxun.test/storage/default_avatars/pic_020.jpg",
            "description": "",
            "level": 0,
            "score": "2.0"
        },
        "has_fee_amount": true,
        "created_at": "2019-11-25 14:37:11"
    }
}
```
