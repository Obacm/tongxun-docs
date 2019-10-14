# 图片上传

阿里云单图片上传

## 请求地址

> `file/oss`

## 请求类型

> `POST`

## 请求参数

#### Body

> - `media` 图片数据

#### 响应参数

> - `url` `string` 图片URL

## 响应示例

```json
{
    "data": {
        "url": "https://zchat-app-image.oss-cn-zhangjiakou.aliyuncs.com/XDEUyZOnTyLrpOXZWDQRwUQbt6SDGDKVXPOJptRD.png"
    },
    "ok": 1
}
```