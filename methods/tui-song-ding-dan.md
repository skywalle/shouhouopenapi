# 创建订单

# 说明

创建订单

# 请求地址

branch/trade/create

# 支持格式

普通Form

# HTTP请求方式

POST

# 是否需要授权

是

# 请求参数

| 名称 | 类型 | 必须 | 描述 |
| --- | --- | --- | --- |
| Contact | Object | 是 | 联系信息 |
| ReserveTime | DateTime | 是 | 预约时间 |
| ProductInfo | Object | 是 | 产品品类信息 |
| FaultType | string | 否 | 故障类型 |
| BuyChnnal | string | 否 | 购买渠道 |
| ServiceType | Object | 是 | 服务类型 |
| BuyTime | DateTime | 否 | 购买时间 |
|  |  |  |  |

# 注意事项

# 返回结果

结果对象，详情见返回结果说明。

```

```

## 返回结果说明 {#返回结果说明}

| 返回字段 | 字段类型 | 字段说明 |
| :--- | :--- | :--- |
| Status | Object | 状态名称 |
| Value | Object | 结果值 |
| ResultTime | Object | 返回时间 |
| error | Object | 错误信息 |
| error\_description | Object | 错误描述 |



