# 通知列表

获取远程通知记录

## 请求地址

> `notifications`

## 请求类型

> `GET`

## 请求参数

#### Header

> - `Authorization` `Bearer access_token` 授权token

#### Query

> - `type` 类型 `task_notification: 任务通知 system_notification: 系统通知` 

## 响应示例

```json
{
    "data": [
        {
            "id": "d6d7ccef-1d44-471b-98bd-5bc2e36f29c5",
            "type": "task_cancel_notification",
            "data": {
                "type": 2073,
                "data": {
                    "id": 84,
                    "name": "任务订单反馈",
                    "title": "225",
                    "user": "哈哈哈",
                    "remark": "您的任务已失效",
                    "created_at": "2019-12-13 10:25:13"
                }
            }
        },
        {
            "id": "077b8096-4e0c-4302-8a23-2771b2021c2a",
            "type": "task_invite_applier_notification",
            "data": {
                "type": 2031,
                "data": {
                    "id": 84,
                    "name": "任务订单反馈",
                    "title": "225",
                    "user": "哈哈哈",
                    "applier": "贾海然",
                    "remark": "您已同意对方的任务邀接",
                    "applied_at": "2019-12-16 13:51:05"
                }
            }
        },
        {
            "id": "d4980be9-73e4-4a33-8bfd-cbb5f05eb677",
            "type": "task_invite_user_notification",
            "data": {
                "type": 2032,
                "data": {
                    "id": 84,
                    "name": "任务订单反馈",
                    "title": "225",
                    "user": "哈哈哈",
                    "applier": "贾海然",
                    "remark": "对方已同意您的任务邀接",
                    "applied_at": "2019-12-16 13:51:05"
                }
            }
        },
        {
            "id": "9018ca42-8f2f-49fb-bf52-55da99408b32",
            "type": "task_cancel_notification",
            "data": {
                "type": 2073,
                "data": {
                    "id": 87,
                    "name": "任务订单反馈",
                    "title": "1234",
                    "user": "贾海然",
                    "remark": "您的任务已失效",
                    "created_at": "2019-12-16 13:32:10"
                }
            }
        },
        {
            "id": "c353e7c0-e525-4ecb-a7a6-2d7b028be92a",
            "type": "task_cancel_notification",
            "data": {
                "type": 2073,
                "data": {
                    "id": 87,
                    "name": "任务订单反馈",
                    "title": "1234",
                    "user": "贾海然",
                    "remark": "您的任务已失效",
                    "created_at": "2019-12-16 13:32:10"
                }
            }
        },
        {
            "id": "2f1bd87f-afa4-45fc-a975-083590acc37f",
            "type": "task_invite_applier_notification",
            "data": {
                "type": 2031,
                "data": {
                    "id": 87,
                    "name": "任务订单反馈",
                    "title": "1234",
                    "user": "贾海然",
                    "applier": "哈哈哈",
                    "remark": "您已同意对方的任务邀接",
                    "applied_at": "2019-12-16 13:33:14"
                }
            }
        },
        {
            "id": "8f2aa9b1-852b-4e77-98e8-b6b446c52e4b",
            "type": "task_invite_user_notification",
            "data": {
                "type": 2032,
                "data": {
                    "id": 87,
                    "name": "任务订单反馈",
                    "title": "1234",
                    "user": "贾海然",
                    "applier": "哈哈哈",
                    "remark": "对方已同意您的任务邀接",
                    "applied_at": "2019-12-16 13:33:14"
                }
            }
        },
        {
            "id": "f13cae6f-905e-4f91-8b89-2fe4155b72a9",
            "type": "task_published_notification",
            "data": {
                "type": 2000,
                "data": {
                    "id": 87,
                    "name": "任务发布成功",
                    "title": "1234",
                    "user": "贾海然",
                    "remark": "您的任务已成功发布",
                    "created_at": "2019-12-16 13:32:10"
                }
            }
        },
        {
            "id": "5a8f1f83-3a79-40a3-bb7b-3cd9512e4314",
            "type": "task_invite_applier_notification",
            "data": {
                "type": 2031,
                "data": {
                    "id": 86,
                    "name": "任务订单反馈",
                    "title": "邀接",
                    "user": "陈杰",
                    "applier": "哈哈哈",
                    "remark": "您已同意对方的任务邀接",
                    "applied_at": "2019-12-16 11:28:37"
                }
            }
        },
        {
            "id": "a6fd387e-3b23-4c6f-90aa-2c0a7f37f97b",
            "type": "task_invite_user_notification",
            "data": {
                "type": 2032,
                "data": {
                    "id": 86,
                    "name": "任务订单反馈",
                    "title": "邀接",
                    "user": "陈杰",
                    "applier": "哈哈哈",
                    "remark": "对方已同意您的任务邀接",
                    "applied_at": "2019-12-16 11:28:37"
                }
            }
        },
        {
            "id": "c36c8797-65f1-45ca-95b7-2deb4db9a69e",
            "type": "task_published_notification",
            "data": {
                "type": 2000,
                "data": {
                    "id": 86,
                    "name": "任务发布成功",
                    "title": "邀接",
                    "user": "陈杰",
                    "remark": "您的任务已成功发布",
                    "created_at": "2019-12-16 11:28:16"
                }
            }
        },
        {
            "id": "1e4a6675-9f1b-4ae1-8f78-dd3caa145fc3",
            "type": "task_invite_applier_notification",
            "data": {
                "type": 2031,
                "data": {
                    "id": 85,
                    "name": "任务订单反馈",
                    "title": "123",
                    "user": "哈哈哈",
                    "applier": "陈杰",
                    "remark": "您已同意对方的任务邀接",
                    "applied_at": "2019-12-16 11:24:26"
                }
            }
        },
        {
            "id": "f131be33-659b-46a6-868e-02ddcc703e29",
            "type": "task_invite_user_notification",
            "data": {
                "type": 2032,
                "data": {
                    "id": 85,
                    "name": "任务订单反馈",
                    "title": "123",
                    "user": "哈哈哈",
                    "applier": "陈杰",
                    "remark": "对方已同意您的任务邀接",
                    "applied_at": "2019-12-16 11:24:26"
                }
            }
        },
        {
            "id": "84b3aa41-bc0d-499d-80ef-ae36f2af91f4",
            "type": "task_invite_user_notification",
            "data": {
                "type": 2032,
                "data": {
                    "id": 76,
                    "name": "任务订单反馈",
                    "title": "445",
                    "user": "56320cfdf338",
                    "applier": "哈哈哈",
                    "remark": "对方已同意您的任务邀接",
                    "applied_at": "2019-12-16 11:21:29"
                }
            }
        },
        {
            "id": "c6c6b8fd-bd3d-43b5-bc04-6e1e2bedc4cf",
            "type": "task_invite_applier_notification",
            "data": {
                "type": 2031,
                "data": {
                    "id": 76,
                    "name": "任务订单反馈",
                    "title": "445",
                    "user": "56320cfdf338",
                    "applier": "哈哈哈",
                    "remark": "您已同意对方的任务邀接",
                    "applied_at": "2019-12-16 11:21:29"
                }
            }
        }
    ],
    "links": {
        "first": "https://api.wtdoe.com/api/notifications?page=1",
        "last": "https://api.wtdoe.com/api/notifications?page=5",
        "prev": "https://api.wtdoe.com/api/notifications?page=2",
        "next": "https://api.wtdoe.com/api/notifications?page=4"
    },
    "meta": {
        "current_page": 3,
        "from": 31,
        "last_page": 5,
        "path": "https://api.wtdoe.com/api/notifications",
        "per_page": 15,
        "to": 45,
        "total": 70
    },
    "ok": 1
}
```