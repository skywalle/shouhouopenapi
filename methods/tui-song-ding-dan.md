# 推送订单

# 说明

推送订单到kafka

# 请求地址

skyeye\/trade\/sync\/{tradePkId}

# 支持格式

{url}?k1=v1&k2=v2&k3=v3&...

# HTTP请求方式

GET

# 是否需要授权

是

# 请求参数

| 名称 | 类型 | 必须 | 描述 |
| --- | --- | --- | --- |
| tradePkId | Guid | no | 订单PkId |



# 注意事项

暂无

# 返回结果

string:

“成功了”  or “失败了” + 错误信息

