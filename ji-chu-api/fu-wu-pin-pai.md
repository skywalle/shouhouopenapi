# 服务品牌

# 说明

获取品牌商列表

# 请求地址

manage/webdoc/brand/page

# 支持格式

QueryString：

{url}?k1=v1&k2=v2&k3=v3&... 

# HTTP请求方式

GET

# 是否需要授权

是，系统管理组

# 请求参数

| 名称 | 类型 | 必选 | 描述 |
| --- | --- | --- | --- |
| sort | string | no | 排序字段 |
| order | bool | no | true  or false |
| limit | int | 每页数据条数 | 分页时每页数据条数 |
| offset | int | 行数偏移量 | 分页请求时行数偏移量 |

# 注意事项

1.请求用户需在“系统管理组”内。

2.返回数据为分页数据，其中分页索引PageIndex = \(offset / limit\) + 1;

# 返回结果

```
{
  "PageIndex": 1,
  "PageSize": 10,
  "PageCount": 18,
  "DataCount": 173,
  "DataName": null,
  "DateDesc": null,
  "IsSelect": null,
  "DataRows": [
    {
      "PkId": "84211b38-cd6a-ccf5-da87-28e60d2cf54b",
      "Title": "AOC",
      "TitlePic": "http://surdataoss.oss-cn-qingdao.aliyuncs.com/cs/webdoc/636264652527083798.jpg",
      "Category": "电视",
      "ReadCount": null,
      "BrandLogo": "http://surdataoss.oss-cn-qingdao.aliyuncs.com/cs/webdoc/636264652413089634.jpg",
      "BrandContent": null,
      "WapSiteQr": null,
      "BrandSort": 0,
      "BrandType": "冠捷（AOC） "
    },
    ...
  ],
  "total": 173
}
```

## 返回结果说明 {#返回结果说明}

| 返回字段 | 字段类型 | 字段说明 |
| :--- | :--- | :--- |
| PageIndex | int | 页面索引值 |
| PageSize | int | 每页数据条目数 |
| PageCount | int | 数据记录总页数 |
| DataCount | int | 数据记录总条目数 |
| total | int | 同DataCount |

DataRows 字段说明：

| 返回字段 | 字段类型 | 字段说明 |
| :--- | :--- | :--- |
| PkId | Guid | 品牌主键 |
| Title | string | 品牌主题 |
| TitlePic | string | 主题图片 |
| Category | string | 品牌分类 |
| ReadCount | int | 阅读数 |
| BrandLogo | string | 品牌Logo |
| BrandContent | string | 品牌正文 |
| WapSiteQr | string | WAP站二维码 |
| BrandSort | int | 品牌排序 |
| BrandType | string | 品牌类型 |



