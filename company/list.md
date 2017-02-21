##保洁员列表

### 说明

| Key      | Value                       |
|:---------|:----------------------------|
| 功能描述 |保洁公司列表          |
| 接口地址 | /baojie/company/list |
| 调用方式 | GET                        |

### 参数

| 参数 | 类型    | 描述 | 说明            | 可空 |
|:-----|:--------|:-----|:----------------|:-----|
| page | integer | 分页 | 从1开始,默认为1 | Y    |
| keyword | string | 关键字 | 模糊查询 | Y    |

### 接口返回值

```json
{

    "resultCode": 0,
    "resultMsg": "success",
    "result": {
        "currentPage": 1,
        "totalPages": 1,
        "total": 3,
        "items": [
            {
                "id": 2,
                "name": "保洁公司名字",
                "chargeMan": "负责人",
                "mobile": "手机号",
                "email": "邮件",
                "loginName": "登录名",
                "loginPassword": "登录密码(加密过)",
                "ymsUserId": "yms系统用户id",
                "deleted_at": null,
                "createUserID": "5579518dcaa8219c3a8b4568",
                "createUserName": "测试",
                "createDate": "2016-12-29 17:11:26",
                "updateUserID": "5579518dcaa8219c3a8b4568",
                "updateUserName": "测试",
                "updateDate": "2016-12-29 17:11:26",
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
