# 手续费

提现时产生的手续费

## 请求地址

> `trade/withdraw/charge`

## 请求类型

> `POST`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Body

> - `amount` `string` 金额

## 响应参数

> - `amount` `float` 原始金额
> - `charge_amount` `float` 实际到账金额
> - `charge_amount` `float` 手续费

## 响应示例

```json
{
    "data": {
        "amount": 0.1,
        "actual_amount": 0.1,
        "charge_amount": 0.1
    },
    "ok": 1
}
```