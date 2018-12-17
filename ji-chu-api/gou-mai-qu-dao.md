# 购买渠道

# 说明

获取产品购买渠道.

# 请求地址

site/trade/buy/channel/list

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

无

# 返回结果

```
[
  {
    "PkId": "12ad5c79-0444-f889-66c2-faf90e73d8c9",
    "Name": "淘宝",
    "TradePkId": null,
    "IsBranch": null
  },
  {
    "PkId": "35c44bc0-c7af-f5ae-6e73-b195f933810e",
    "Name": "天猫",
    "TradePkId": null,
    "IsBranch": null
  },
  ...
]
```

## 返回结果说明 {#返回结果说明}

| 返回字段 | 字段类型 | 字段说明 |
| --- | --- | --- |
| PkId | Guid | 主键 |
| Name | string | 购买渠道名称 |
| TradeId | Guid | 订单PkId，暂未使用 |
| IsBranch | bool | 是否是网点，暂未使用 |



