# 概括

## 访问地址

> `https://api.wtdoe.com/api`

## 客户端区分

### 请求头 X-Client

> 安卓: Android

> 苹果: iOS

## 服务器异常响应


> :heart: 系统错误

```json
{
    "errno": 10001,
    "msg": "系统错误",
    "ok": 0
}
```

> :heart: 服务不可用

```json
{
    "errno": 10002,
    "msg": "服务不可用",
    "ok": 0
}
```

> :heart: 接口不存在

```json
{
    "errno": 10003,
    "msg": "接口不存在",
    "ok": 0
}
```

> :heart: IP请求频次超过上限

```json
{
    "errno": 10004,
    "msg": "IP请求频次超过上限",
    "ok": 0
}
```

> :heart: 用户请求频次超过上限

```json
{
    "errno": 10005,
    "msg": "用户请求频次超过上限",
    "ok": 0
}
```

> :heart: 用户请求频次超过上限

```json
{
    "errno": 10005,
    "msg": "用户请求频次超过上限",
    "ok": 0
}
```

> :heart: 参数值非法

```json
{
    "errno": 10006,
    "msg": "参数值非法",
    "ok": 0
}
```

> :heart: 登录令牌已过期

```json
{
    "errno": 10007,
    "msg": "登录令牌已过期",
    "ok": 0
}
```

> :heart: 用户权限不足

```json
{
    "errno": 10008,
    "msg": "用户权限不足",
    "ok": 0
}
```

> :heart: 短信接口触发限制

```json
{
    "errno": 10009,
    "msg": "短信接口触发限制",
    "ok": 0
}
```

> :heart: 账号被封禁中

```json
{
    "errno": 10010,
    "msg": "账号被封禁中",
    "ok": 0
}
```

> :heart: 用户不存在

```json
{
    "errno": 20001,
    "msg": "用户不存在",
    "ok": 0
}
```

> :heart: 发布内容过于频繁

```json
{
    "errno": 20002,
    "msg": "发布内容过于频繁",
    "ok": 0
}
```

> :heart: 提交相同的信息

```json
{
    "errno": 20003,
    "msg": "提交相同的信息",
    "ok": 0
}
```

> :heart: 验证码错误

```json
{
    "errno": 20005,
    "msg": "验证码错误",
    "ok": 0
}
```

> :heart: 请求数据不存在

```json
{
    "errno": 20006,
    "msg": "请求数据不存在",
    "ok": 0
}
```

> :heart: 未实名认证

```json
{
    "errno": 20031,
    "msg": "未实名认证",
    "ok": 0
}
```

> :heart: 已设置支付密码

```json
{
    "errno": 20032,
    "msg": "已设置支付密码",
    "ok": 0
}
```

> :heart: 尚未设置支付密码

```json
{
    "errno": 20033,
    "msg": "尚未设置支付密码",
    "ok": 0
}
```