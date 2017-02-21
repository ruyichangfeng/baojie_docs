##保洁公司详情

### 说明

| Key      | Value                       |
|:---------|:----------------------------|
| 功能描述 |保洁公司详情          |
| 接口地址 | /baojie/company/detail/{id} |
| 调用方式 | GET                        |

### 参数

| 参数 | 类型    | 描述 | 说明            | 可空 |
|:-----|:--------|:-----|:----------------|:-----|
| id | integer |保洁公司ID |  | N    |


### 接口返回值

```json
{

    "resultCode": 0,
    "resultMsg": "查询成功!",
    "result": {
        "basicInfo": {
            "name": "名字",
            "chargeMan": "负责人",
            "mobile": "手机号",
            "email": "邮箱"
        },
        "loginInfo": {
            "loginName": "登录名",
            "loginPassword": "密码"
        }
    }

}
```
