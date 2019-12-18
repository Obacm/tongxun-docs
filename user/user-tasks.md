# 获取他的任务

获取一个用户信息

## 请求地址

> `user/[id]/tasks`

##### <font color="blue">须知</font>

> {warning} [id] 表示用户ID 需要把用户ID 拼接在 `users/` 后面

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

## 响应示例

```json
{
    "data": [
        {
            "id": 12,
            "task_no": "TS_20191218173013425625",
            "title": "嘻嘻哈哈哈哈",
            "state": 1,
            "published_at": "2019-12-18 17:30:13"
        },
        {
            "id": 11,
            "task_no": "TS_20191218173011586466",
            "title": "嘻嘻哈哈哈哈",
            "state": 1,
            "published_at": "2019-12-18 17:30:11"
        },
        {
            "id": 10,
            "task_no": "TS_20191218172834940649",
            "title": "嘻嘻哈哈哈哈",
            "state": 1,
            "published_at": "2019-12-18 17:28:34"
        }
    ],
    "links": {
        "first": "http://api.tongxun.test/api/user/7/tasks?page=1",
        "last": "http://api.tongxun.test/api/user/7/tasks?page=1",
        "prev": null,
        "next": null
    },
    "meta": {
        "current_page": 1,
        "from": 1,
        "last_page": 1,
        "path": "http://api.tongxun.test/api/user/7/tasks",
        "per_page": 15,
        "to": 3,
        "total": 3
    },
    "ok": 1
}
```