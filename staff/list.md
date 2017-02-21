##保洁员列表

### 说明

| Key      | Value                       |
|:---------|:----------------------------|
| 功能描述 | 保洁员列表          |
| 接口地址 | /baojie/staff/list |
| 调用方式 | GET                        |

### 参数

| 参数 | 类型    | 描述 | 说明            | 可空 |
|:-----|:--------|:-----|:----------------|:-----|
| page | integer | 分页 | 从1开始,默认为1 | Y    |
| keyword | string | 关键字 | 模糊查询 | Y    |
| companyID | integer | 保洁公司ID |  | Y    |

### 接口返回值

```json
{

    "resultCode": 0,
    "resultMsg": "success",
    "result": {
        "currentPage": "当前页",
        "totalPages": "总页数",
        "total": "总数",
        "items": [
            {
                "id": "保洁员ID",
                "name": "保洁员名字",
                "sex": "性别",
                "mobile": "手机号",
                "img": "图片",
                "companyID": "保洁公司ID",
                "deleted_at": null,
                "createUserID": "5579518dcaa8219c3a8b4568",
                "createUserName": "测试",
                "createDate": "2016-12-29 16:26:43",
                "updateUserID": "5579518dcaa8219c3a8b4568",
                "updateUserName": "测试",
                "updateDate": "2016-12-29 16:26:43",
                "bjCompanyName": "保洁公司名字",
                "analyzer": "分词字段",
                "actionAuths": {
                    "isUpdate": "编辑权限",
                    "isDetail": "详情权限"
                }
            }
        ],
        "propertyCount": "物业数量",
        "actionAuths": {
            "isCreate": "创建权限"
        }
    }

}
```
