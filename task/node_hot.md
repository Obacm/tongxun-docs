# 热门任务分类

获取任务圈热门分类

## 请求地址

> `task/nodes/hot`

## 请求类型

> `GET`

## 响应参数

> - `id` `int` 分类
> - `name` `string` 分类名
> - `icon` `string` 图标

## 响应示例

```json
{
    "data": [
        {
            "id": 1,
            "name": "保洁清洗 ",
            "icon": "https://api.wtdoe.com/storage/node_icons/bao_jie_qing_xi.png",
            "hot": 1
        },
        {
            "id": 4,
            "name": "房屋维修",
            "icon": "https://api.wtdoe.com/storage/node_icons/fang_wu_zhaung_xiu.png",
            "hot": 1
        },
        {
            "id": 5,
            "name": "家电维修",
            "icon": "https://api.wtdoe.com/storage/node_icons/jia_dian_wei_xiu.png",
            "hot": 1
        },
        {
            "id": 7,
            "name": "上门安装",
            "icon": "https://api.wtdoe.com/storage/node_icons/shang_men_an_zhuang.png",
            "hot": 1
        },
        {
            "id": 0,
            "name": "全部分类",
            "icon": "https://api.wtdoe.com/storage/node_icons/all.png",
            "hot": 1
        }
    ],
    "ok": 1
}
```

