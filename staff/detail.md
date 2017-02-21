## 保洁员详情

### 说明

| Key      | Value                       |
|:---------|:----------------------------|
| 功能描述 | 保洁员详情          |
| 接口地址 | /baojie/staff/detail/{id} |
| 调用方式 | GET                        |

### 参数

| 参数 | 类型    | 描述 | 说明            | 可空 |
|:-----|:--------|:-----|:----------------|:-----|
| id | integer | 保洁员ID |  | N    |


### 接口返回值

```json
{

    "resultCode": 0,
    "resultMsg": "查询成功!",
    "result": {
        "basicInfo": {
            "id": "保洁员ID",
            "bjCompanyID": "保洁公司ID",
            "bjCompanyName": "保洁公司名字",
            "name": "保洁员名字",
            "sexName": "性别",
            "sex": "性别id",
            "mobile": "手机号",
            "img": "头像"
        }
    }

}
```
