# 语音搜索 --- 任务 && 问答

根据文字检索任务与问答

## 请求地址

> `complex/search`

## 请求类型

> `GET`

## 请求参数

#### Query

> - `keyword` `string` 关键字

## 响应示例

```json
{
    "data": {
        "tasks": [
            {
                "id": 10,
                "task_no": "TS_20191218172834940649",
                "title": "嘻嘻哈哈哈哈",
                "hire_amount": "10.00",
                "fee_amount": "0.00",
                "description": "卧槽这的可以这个",
                "state": 1,
                "has_fee_amount": false,
                "published_at": "2019-12-18 17:28:34"
            },
            {
                "id": 11,
                "task_no": "TS_20191218173011586466",
                "title": "嘻嘻哈哈哈哈",
                "hire_amount": "10.00",
                "fee_amount": "0.00",
                "description": "卧槽这的可以这个",
                "state": 1,
                "has_fee_amount": false,
                "published_at": "2019-12-18 17:30:11"
            }
        ],
        "questions": []
    },
    "ok": 1
}
```
