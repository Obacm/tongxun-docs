# 红包检查

红包检查 判断当前红包状态

## 请求地址

> `packet/[id]/check`

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
    "type": 0,
    "state": 1,
    "ok": 0
}
```

```json
{
    "msg": "红包已经过期了",
    "type": 0,
    "state": 2,
    "ok": 0
}
```

```json
{
    "msg": "已抢到过红包了",
    "type": 1,
    "state": 3,
    "ok": 0
}
```

```json
{
    "msg": "等待对方领取",
    "type": 1,
    "state": 4,
    "ok": 0
}
```