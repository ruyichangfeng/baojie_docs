## 保洁单列表

### 说明

| Key      | Value                       |
|:---------|:----------------------------|
| 功能描述 | 保洁单列表          |
| 接口地址 | /baojie/order/list |
| 调用方式 | GET                        |

### 参数

| 参数 | 类型    | 描述 | 说明            | 可空 |
|:-----|:--------|:-----|:----------------|:-----|
| page | integer | 分页 | 从1开始,默认为1 | Y    |
| keyword | string | 关键字 | 模糊查询 | Y    |
| companyID | integer | 保洁公司ID |  | Y    |
| bjOperatorID | integer | 保洁员ID |  | Y    |

### 接口返回值

```json
{
  "resultCode": 0,
  "resultMsg": "success",
  "result": {
    "currentPage": "当前页",
    "totalPages": "总页数",
    "total": "总计",
    "items": [
      {
        "id": "订单ID",
        "type": "保洁类型",
        "propertyBH": "物业编号",
        "storeID": "门店ID",
        "storeName": "门店名字",
        "communityID": "小区ID",
        "communityName": "小区名字",
        "propertyAddress": "物业地址",
        "bjCompanyID": "保洁公司ID",
        "bjOperatorID": "保洁员ID",
        "cleanStartDate": "要求保洁开始日期",
        "cleanEndDate": "要求保洁结束日期",
        "realCleanStartDate": "实际开始日期",
        "realCleanEndDate": "实际结束日期",
        "cleanImgs": "保洁图片",
        "getKeysTime": "获取钥匙时间",
        "backKeysTime": "还钥匙时间",
        "checkDate": "验收日期",
        "checkManID": "验收人员id",
        "checkManName": "验收人员名字",
        "checkResultType": "验收类型",
        "checkResultRemark": "验收备注",
        "checkImgs": "验收图片",
        "cancelReason": "取消原因",
        "orderStatus": "订单状态",
        "roomName": "客房名字",
        "rentType": "出租类型",
        "keysNumber": "钥匙数量",
        "remark": "备注",
        "lat": "经度",
        "lng": "纬度",
        "deleted_at": null,
        "createUserID": "5579518dcaa8219c3a8b4568",
        "createUserName": "测试",
        "createDate": "2016-12-30 14:11:27",
        "updateUserID": "5629c6ddcaa821177e8b457a",
        "updateUserName": "张笑",
        "updateDate": "2016-12-30 14:11:27",
        "bjOperatorName": "保洁员名字",
        "bjCompanyName": "保洁公司名字",
        "isBackKeys": "是否归还钥匙",
        "isUploadCleanImg": "是否上传保洁图片",
        "askCleanDate": "要求保洁日期",
        "typeName": "保洁类型名字",
        "checkResultName": "验收结果",
        "orderStatusName": "订单状态名字",
        "score": "租客评分",
        "analyzer": "分词字段",
        "actionAuths": {
          "isCancelBj": "取消权限",
          "isStartBj": "开始权限",
          "isDetail": "详情权限",
          "isBackKeys": "归还权限",
          "isUpdate": "更新权限"
        }
      }
    ],
    "propertyCount": "物业数量",
    "actionAuths": {
      "isCreate": "创建权限",
      "isImport": "导入权限",
      "isExport": "导出权限"
    }
  }
}
```
