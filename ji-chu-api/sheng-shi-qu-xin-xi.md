# 获取省市区

# 说明

1、获取全量省市区列表

# 请求地址

common/region/list/province

# 支持格式

{url}

无需传递参数

# HTTP请求方式

GET

# 是否需要授权

否

# 请求参数

暂无

# 注意事项

暂无

# 返回数据

```
Sample:
[
  {
    "PkId": 110000,  /*区域ID*/
    "AreaName": "北京",
    "ParentId": 0,  /*区域父子关系，0表示一级；与PkId关联*/
    "ShortName": "北京",
    "Lng": 1.0,  /*经度*/
    "Lat": 1.0,  /*纬度*/
    "Level": 1,  /*层级：省=1，区级市=2，地级市=3，镇=4*/
    "Sort": 1    /*同一Level排序，升序*/
  },
  ...
]
```

## 返回结果说明 {#返回结果说明}

| 返回字段 | 字段类型 | 字段说明 |
| --- | --- | --- |
| PkId | int | 区域主键Id |
| AreaName | string | 区域名称 |
| ParentId | int | 上级区域Id |
| ShortName | string | 区域名称简称 |
| Lng | decimal | 经度 |
| Lat | decimal | 维度 |
| Level | int | 省=1，区域市=2，地级市=3，乡镇=4 |
| Sort | int | 同一等级区域的排序 |



