## 保洁单详情

### 说明

| Key      | Value                       |
|:---------|:----------------------------|
| 功能描述 | 保洁单详情          |
| 接口地址 | /baojie/detail/detail/{id} |
| 调用方式 | GET                        |

### 参数

| 参数 | 类型    | 描述 | 说明            | 可空 |
|:-----|:--------|:-----|:----------------|:-----|
| id | integer | 保洁单ID |  | N    |


### 接口返回值

```json
{

    "resultCode": 0,
    "resultMsg": "查询成功!",
    "result": {
        "basicInfo": {
            "propertyBH": "物业编号",
            "propertyAddress": "物业地址",
            "storeName": "门店名字",
            "storeID": "门店ID",
            "communityName": "小区名字",
            "roomName": "客房名字",
            "rentType": "出租类型",
            "bjCompany": "保洁公司",
            "bjCompanyID": "保洁公司id",
            "bjOperatorID": "保洁员ID",
            "bjOperatorName": "保洁员名字",
            "cancelReason": "取消原因",
            "remark": "备注",
            "askCleanTime": "要求保洁日期",
            "type": "保洁类型",
            "typeName": "保洁类型名称",
            "orderStatus": "订单状态",
            "orderStatusName": "订单状态名字",
            "cleanArea": "保洁区域"
        },
        "time": {
            "askCleanTime": "要求保洁日期",
            "getKeysTime": "领取钥匙时间",
            "cleanEndTime": "保洁结束时间",
            "backKeysTime": "回收钥匙时间",
            "checkTime": "管家验收时间"
        },
        "bjImgs": "保洁图片",
        "checkResult": {
            "checkMan": "验收人员",
            "checkResult": "验收结果",
            "checkImgs": "验收图片"
        },
        "customerScore": "租客评论"
    }

}
```
