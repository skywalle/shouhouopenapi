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
    "PkId": "a902ef50-3a8c-1f07-89fb-f36c1b396624",
    "Name": "测试额额",
    "Sort": null,
    "CreateTime": "2017-08-04 18:09:41",
    "ProductType": {
      "PkId": "c7c1750b-26ea-636d-9b7b-4a3bccb22257",
      "NameIcon": null,
      "Name": "生活家电",
      "SystemNumber": null,
      "Sort": null,
      "CreateTime": "2017-05-15 09:12:54",
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
    },
    "ProductBrand": null,
    "ProductCategory": {
      "PkId": "a1b7b03a-3544-dd36-946f-c51da32b9127",
      "Name": "微波炉",
      "SystemNumber": null,
      "NameIcon": null,
      "Sort": null,
      "ProductBrand": null,
      "ProductType": null,
      "CreateTime": "2017-05-15 09:13:24",
      "UpdateTime": null,
      "FaultList": null,
      "IsSelected": null,
      "TradePkId": null,
      "ParentId": "c7c1750b-26ea-636d-9b7b-4a3bccb22257",
      "ParentSubPkId": null,
      "ProductInfo": null,
      "IsSystemHas": true,
      "OwnerProductTypePkId": null,
      "FkBrandsSellerPkId": null,
      "BrandsSellerName": null,
      "FkBranchSellerPkId": null,
      "BranchSellerName": null,
      "SystemPublickPkId": null,
      "ServiceMethod": null,
      "CategoryTitlePic": null
    },
    "ProductInfo": null,
    "SerialNumber": null,
    "ProductModel": null,
    "ProductModelOne": null,
    "FaultProblem": null,
    "FaultReason": null,
    "BuyTime": null,
    "FormatTime": null,
    "BuyChannel": null,
    "ServiceCount": null,
    "FwMethod": null,
    "ServiceMethod": null,
    "FwContent": null,
    "FkBrandsSellerPkId": null,
    "BrandsSellerName": null,
    "FkBranchSellerPkId": null,
    "BranchSellerName": null,
    "ErrorInfo": null,
    "IsSelected": null,
    "IsSystemHas": true,
    "SystemNumber": "1121",
    "ParentId": "a1b7b03a-3544-dd36-946f-c51da32b9127",
    "MaintenanceCycle": null,
    "OwnerProductInfoPkId": null,
    "CategoryTitlePic": null,
    "SystemSpecificationPkId": null
  }
]
```

## 返回结果说明 {#返回结果说明}

| 返回字段 | 字段类型 | 字段说明 |
| :--- | :--- | :--- |
| PkId | Guid | 主键 |
| TradePkId | Guid | 订单PkId |
| Name | string | 产品品类名称 |
| Sort | int | 排序 |
| CreateTime | DateTime | 创建日期 |
| PorductType | Object | 所属产品分类 |
| ProductCategory | Object | 所属产品线 |
| ProductBrand | Object | 产品品牌，暂未使用 |
| ProductInfo | Object | 产品品类，暂未使用 |
| SerialNumber | string | 序列号 |
| ProductModel | Object | 产品型号，暂未使用 |
| ProductModelOne | Object | 产品型号单个，暂未使用 |
| FaultProblem | string | 故障现象，暂未使用 |
| FaultReason | string | 故障原因，暂未使用 |
| BuyTime | DateTime | 购买日期，暂未使用 |
| ServiceCount | int | 服务次数，暂未使用 |
| FwMethod | Object | 服务措施，暂未使用 |
| ServiceMethod | Object | 服务措施列表，暂未使用 |
| FwContent | string | 服务描述，暂未使用 |
| FkBrandsSellerPkId | Guid | 品牌商用户PkId，暂未使用 |
| BrandsSellerName | string | 品牌商用户名称，暂未使用 |
| ErrorInfo | string | 错误信息，暂未使用 |
| IsSelected | bool | 是否选中，暂未使用 |
| IsSystemHas | bool | 是否系统默认 |
| SystemNumber | string | 系统编号 |
| ParentId | Guid | 父级ID |
| MaintenanceCycle | decimal | 保养周期，暂未使用 |
| OwnerProductInfoPkId | Guid | 自己的产品品类编号，暂未使用 |
| CategoryTitlePic | string | 产品线图片，暂未使用 |
| SystemSpecificationPkId | Guid | 系统原始编码，暂未使用 |

ProductType（产品分类）：



ProductCategory（产品线）：



