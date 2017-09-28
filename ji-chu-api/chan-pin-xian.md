# 产品线

# 说明

获取产品线列表

# 请求地址

manager/product/category/list

# 支持格式

{url}

无需传递参数

# HTTP请求方式

GET

# 是否需要授权

是，系统管理组

# 请求参数

无

# 注意事项

请求的用户必须拥有“系统管理组”角色。

# 返回结果

```
[
  {
    "PkId": "48bdf2f9-4084-f206-d68c-cb93f1d61846",
    "Name": "冰箱",
    "SystemNumber": "20170807",
    "NameIcon": null,
    "Sort": null,
    "ProductBrand": null,
    "ProductType": null,
    "CreateTime": "2017-08-07 09:22:16",
    "UpdateTime": null,
    "FaultList": null,
    "IsSelected": null,
    "TradePkId": null,
    "ParentId": "7c2b50fc-507c-329c-552b-7b1c0ff2aab2",
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
    "CategoryTitlePic": "http://oss.surdata.com/cs/common/636376945365453991.jpg"
  },
  ...
]
```

## 返回结果说明 {#返回结果说明}

| 返回字段 | 字段类型 | 字段说明 |
| :--- | :--- | :--- |
| PkId | Guid | 产品线PkId |
| Name | string | 产品线名称 |
| SystemNumber | string | 编码 |
| NameIcon | string | 名称Icon |
| Sort | int | 排序 |
| CreateTime | DateTime | 创建时间 |
| UpdateTime | DateTime | 更新时间 |
| ParentId | Guid | 上级分类ID |
| CategoryTitlePic | string | 产品线图片 |
| FaultList | Object | 故障类型，暂未使用 |
| IsSelected | bool | 是否选中，暂未使用 |
| TradePkId | Guid | 订单主键ID |



