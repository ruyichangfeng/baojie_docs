##保洁公司创建接口

### 说明

| Key      | Value                   |
|:---------|:------------------------|
| 功能描述 | 创建保洁单      |
| 接口地址 | /baojie/company/create |
| 调用方式 | POST                     |

### 参数

| 参数 | 类型    | 描述     | 说明 | 可空 |
|:-----|:--------|:---------|:-----|:-----|
| name   | string | 名字 |      | N    |
| chargeMan   | string | 负责人 |      | N    |
| mobile   | string | 手机号 |      | N    |
| email   | string | 邮箱 |      | N    |
| loginName   | string | 登录名 |      | N    |
| loginPassword   | string | 登录密码|      | N    |

### 接口返回值

```json
{
    //返回状态码,非0时为错误
    "resultCode": 0,
    "resultMsg": "操作成功",
    "result": {
        "id": "保洁公司ID"
    }
}
```