# 抢红包

领取红包

## 请求地址

> `packet/[id]/seize`

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

## 异常响应示例

```json
{
    "msg": "红包已经被抢完了",
    "ok": 0
}
```

```json
{
    "msg": "红包已经过期了",
    "ok": 0
}
```

```json
{
    "msg": "已抢到过红包了",
    "ok": 0
}
```