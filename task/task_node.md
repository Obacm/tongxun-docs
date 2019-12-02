# 任务圈主分类

获取任务圈首页的任务主分类

## 请求地址

> `task/nodes/hot`

## 请求类型

> `GET`

## 请求参数

## 响应参数

> - `id` `int` 分类ID
> - `name `string` 分类名

## 响应示例

```json
{
    "data": [
        {
            "id": 1,
            "name": "便民服务",
            "hot": 1
        },
        {
            "id": 2,
            "name": "家政服务",
            "hot": 1
        }
    ],
    "ok": 1
}
```

