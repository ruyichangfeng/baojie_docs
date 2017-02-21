## 保洁单创建接口

### 说明

| Key      | Value                   |
|:---------|:------------------------|
| 功能描述 | 创建保洁单      |
| 接口地址 | /baojie/order/create |
| 调用方式 | POST                     |

### 参数

| 参数 | 类型    | 描述     | 说明 | 可空 |
|:-----|:--------|:---------|:-----|:-----|
| propertyBH   | string | 物业编号 |      | N    |
| type   | string | 保洁类型 |      | N    |
| cleanStartDate   | string | 保洁开始日期 |      | N    |
| bjCompanyID   | string | 保洁公司id |      | N    |
| bjOperatorID   | string | 保洁员id |      | N    |
| roomName   | string | 客房名字(开荒保洁必须) |      | N    |
| communityID   | string | 小区id |      | N    |
| communityName   | string | 小区名字 |      | N    |
| storeID   | string | 门店id |      | N    |
| storeName   | string | 门店名字 |      | N    |
| propertyAddress   | string | 物业地址 |      | N    |
| propertyID   | string | 物业ID |      | N    |

### 接口返回值

```json
{
    //返回状态码,非0时为错误
    "resultCode": 0,
    "resultMsg": "操作成功",
    "result": {
        "id": "保洁单ID"
    }
}
```