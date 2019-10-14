# 概括

## 访问地址

> `https://api.wtdoe.com/api`

## 服务器异常响应

> :heart: 请求路径不对

```json
{
    "msg": "Not Found Http Request.",
    "ok": 0
}
```

> :heart: 服务器内部错误

```json
{
    "msg": "Server Error",
    "ok": 0
}
```

> :heart: 未授权（请求时未加认证头, 或者token过期）

```json
{
    "msg": "Unauthenticated.",
    "ok": 0
}
```