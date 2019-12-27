# 任务分类

获取所有任务分类

## 请求地址

> `task/nodes`

## 请求类型

> `GET`

## 响应参数

> - `node` `int` 一级分类
> - `modes` `float` 二级分类

## 响应示例

```json
{
    "data": [
        {
            "node": {
                "id": 0,
                "name": "热门服务",
                "hot": 100
            },
            "modes": [
                {
                    "id": 5,
                    "name": "电脑回收",
                    "node_id": 2
                },
                {
                    "id": 1,
                    "name": "鲜花",
                    "node_id": 1
                },
                {
                    "id": 2,
                    "name": "绿植",
                    "node_id": 1
                }
            ]
        },
        {
            "node": {
                "id": 1,
                "name": "便民服务",
                "hot": 0
            },
            "modes": [
                {
                    "id": 1,
                    "name": "鲜花",
                    "node_id": 1
                },
                {
                    "id": 2,
                    "name": "绿植",
                    "node_id": 1
                },
                {
                    "id": 3,
                    "name": "园艺",
                    "node_id": 1
                }
            ]
        },
        {
            "node": {
                "id": 2,
                "name": "家政服务",
                "hot": 0
            },
            "modes": [
                {
                    "id": 4,
                    "name": "电器回收",
                    "node_id": 2
                },
                {
                    "id": 5,
                    "name": "电脑回收",
                    "node_id": 2
                }
            ]
        }
    ],
    "ok": 1
}
```

