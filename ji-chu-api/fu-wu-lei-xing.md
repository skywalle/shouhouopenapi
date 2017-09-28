# 服务类型

# 说明

获取品牌商服务类型

# 请求地址

brands/service/type/list

# 支持格式

{url}

无需传递参数

# HTTP请求方式

GET

# 是否需要授权

是，在“品牌商组”内。

# 请求参数

无

# 注意事项

请求的用户必须拥有“品牌商组”角色。

# 返回结果

```
[
  {
    "PkId": "617a513c-f789-c016-a19f-b500f2949831",
    "Name": "安装",
    "Sort": null,
    "WebIcon": {
      "Name": "icon-anzhuang",
      "Text": null
    },
    "AppMark": null,
    "DescText": "专业技能，标准服务",
    "CreateTime": null,
    "IsSelected": null,
    "Background": null,
    "IsPortalDisplay": null,
    "IsSystemHas": null,
    "ProductTypes": null,
    "ProductCategorys": null
  },
  {
    "PkId": "e25faf08-d60c-0268-a090-24497ff6e01e",
    "Name": "保养",
    "Sort": null,
    "WebIcon": {
      "Name": "icon-baoyang",
      "Text": null
    },
    "AppMark": null,
    "DescText": "内外清洗，一步到位",
    "CreateTime": null,
    "IsSelected": null,
    "Background": null,
    "IsPortalDisplay": null,
    "IsSystemHas": null,
    "ProductTypes": null,
    "ProductCategorys": null
  },
  {
    "PkId": "7bcfb938-f604-db80-635e-a2bb1fdab850",
    "Name": "维修",
    "Sort": null,
    "WebIcon": {
      "Name": "icon-weixiu",
      "Text": null
    },
    "AppMark": null,
    "DescText": "价格透明，质量保证",
    "CreateTime": null,
    "IsSelected": null,
    "Background": null,
    "IsPortalDisplay": null,
    "IsSystemHas": null,
    "ProductTypes": null,
    "ProductCategorys": null
  }
]
```

## 返回结果说明 {#返回结果说明}

| 返回字段 | 字段类型 | 字段说明 |
| :--- | :--- | :--- |
| PkId | Guid | 服务类型主键 |
| Name | string | 服务类型名称 |
| Sort | int | 服务类型排序 |
| WebIcon | Object | 服务类型前台标识 |
| AppMark | Object | 服务类型程序标识 |
| DescText | string | 服务类型说明 |
| CreateTime | DateTime | 创建时间 |
| Background | string | 背景图片 |
| IsPortalDisplay | bool | 是否显示 |
| IsSystemHas | bool | 是否系统默认 |
| IsSelect | bool | 是否选中，暂未使用 |
| ProductTypes | Object | 产品分类，暂未使用 |
| ProductCategorys | Object | 产品线，暂未使用 |



