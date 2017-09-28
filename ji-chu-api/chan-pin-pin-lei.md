# 产品品类

# 说明

根据产品线获取产品品类

# 请求地址

manager/product/info/list/{productCatePkId}

# 支持格式

{url}/{productCatePkId}

# HTTP请求方式

GET

# 是否需要授权

是，系统管理组

# 请求参数

| 描述 | 类型 | 必选 | 描述 |
| --- | --- | --- | --- |
| productCatePkId | Guid | yes | 产险品PkId |

# 注意事项

暂无

# 返回结果

```
[
  {
    "TradePkId": null,
    "PkId": "caeb4bdd-e7a3-34ac-e878-f2d0a7be03c5",
    "Name": "双开门冰箱",
    "Sort": null,
    "CreateTime": "2017-05-30 21:39:29",
    "ProductType": {
      "PkId": "7c2b50fc-507c-329c-552b-7b1c0ff2aab2",
      "NameIcon": null,
      "Name": "大家电",
      "SystemNumber": null,
      "Sort": 0,
      "CreateTime": "2017-05-16 13:32:24",
      "UpdateTime": null,
      "CateList": null,
      "IsSystemHas": true,
      "IsSelected": null,
      "OwnerProductTypePkId": null,
      "FkBrandsSellerPkId": null,
      "BrandsSellerName": null,
      "FkBranchSellerPkId": null,
      "BranchSellerName": null,
      "SystemPublickPkId": null
    }
  ...
]
```

## 返回结果说明 {#返回结果说明}

| 返回字段 | 字段类型 | 字段说明 |
| :--- | :--- | :--- |
| PkId | Guid | 主键 |
| TradePkId | Guid | 订单PkId |
| Name | string | 产品品类名称 |
| Sort | int | 排序 |
|  |  |  |



