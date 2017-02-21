## 保洁员创建接口

### 说明

| Key      | Value                   |
|:---------|:------------------------|
| 功能描述 | 创建保洁员      |
| 接口地址 | /baojie/staff/create |
| 调用方式 | POST                     |

### 参数

| 参数 | 类型    | 描述     | 说明 | 可空 |
|:-----|:--------|:---------|:-----|:-----|
| companyID   | integer | 保洁公司id |      | N    |
| name   | string | 姓名 |      | N    |
| sex   | integer | 性别 |      | N    |
| mobile   | string | 手机号 |      | N    |
| img   | string | 保洁员图像 |      | N    |
### 接口返回值

```json
{
    //返回状态码,非0时为错误
    "resultCode": 0,
    "resultMsg": "操作成功",
    "result": {
        "id": "保洁员ID"
    }
}
```