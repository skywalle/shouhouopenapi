# 订单查询

# 说明

查询订单列表

# 请求地址

brands/trade/page/{pageIndex}/{pageSize}

# 支持格式

{url}/{pageIndex}/{pageSize}

# HTTP请求方式

GET

# 是否需要授�

是，品牌商组�

# 请求参数

| 名称 | 类型 | 必须 | 描述 |
| --- | --- | --- | --- |
| pageIndex | int | yes | 页面索引 |
| pageSize | int | yes | 页面大小 |

# 注意事项

搜索参数，用QueryString传递�

v = 2 使用新版API接口�

| 名称 | 类型 | 必须 | 描述 |
| --- | --- | --- | --- |
| v | int | yes | 版本号，2 |
| use | string | yes | 使用es查询 |
| ServiceTypeName | string | no | 服务类型 |
| BrandType | string | no | 品牌类型 |
| ProductCategoryName | string | no | 产品线名�|
| TradeStartTime | string | no | 开始时间，格式yyyy-MM-dd HH:mm:ss |
| TradeEndTime | string | no | 开始时间，格式yyyy-MM-dd HH:mm:ss |
| Mobile | string | no | 手机�|
| OrderNum | int | no | 排序 |
| MasterPkId | Guid | no | 师傅PkId |
| TradeChannelName | string | no | 订单渠道 |
| BuyChannel | string | no | 购买渠道 |
| PaymentMethod | string | no | 支付方法 |

# 返回结果

```
{
  "MasterNormalCardCount": null,
  "MasterLateCardCount": null,
  "MasterMissCardCount": null,
  "MasterOutCardCount": null,
  "IsNowDate": null,
  "MasterName": null,
  "PageIndex": 2,
  "PageSize": 10,
  "PageCount": 24,
  "DataCount": 231,
  "DataName": null,
  "DateDesc": null,
  "IsSelect": null,
  "DataRows": [
    {
      "PkId": "8bcc8f7f-1e52-f5b4-3ed3-3c4505adea4d",
      "TradeId": "636348491297724153",
      "TradeNo": null,
      "ServiceType": {
        "TradePkId": "8bcc8f7f-1e52-f5b4-3ed3-3c4505adea4d",
        "PkId": "c51fd394-9f64-6ca0-2835-c756c739c877",
        "Name": "家电安装",
        "Sort": null,
        "WebIcon": {
          "Name": "icon-anzhuang",
          "Text": "专业技能，标准服务"
        },
        "TradeIcon": null,
        "AppMark": null,
        "DescText": null,
        "CreateTime": null,
        "IsSelected": null,
        "Background": null,
        "IsPortalDisplay": null,
        "IsSystemHas": null,
        "ProductTypes": null,
        "ProductCategorys": null
      },
      "ProductInfo": {
        "TradePkId": "8bcc8f7f-1e52-f5b4-3ed3-3c4505adea4d",
        "PkId": "42203b90-65af-8ece-0c1f-a523a1121f74",
        "Name": "双开门冰�,
        "Sort": null,
        "CreateTime": null,
        "ProductType": {
          "PkId": "7c2b50fc-507c-329c-552b-7b1c0ff2aab2",
          "NameIcon": null,
          "Name": "大家�,
          "SystemNumber": null,
          "Sort": null,
          "CreateTime": null,
          "UpdateTime": null,
          "CateList": null,
          "IsSystemHas": null,
          "IsSelected": null,
          "OwnerProductTypePkId": null,
          "FkBrandsSellerPkId": null,
          "BrandsSellerName": null,
          "FkBranchSellerPkId": null,
          "BranchSellerName": null,
          "SystemPublickPkId": null
        },
        "ProductBrand": {
          "PkId": "d12c1c1c-ebd5-893f-9d4a-1b801c219524",
          "Name": "测试品牌",
          "NameIcon": null,
          "ProductTypes": null,
          "ProductCategorys": null,
          "Sort": null,
          "TradePkId": "8bcc8f7f-1e52-f5b4-3ed3-3c4505adea4d",
          "UserId": null,
          "UserName": null,
          "CreateTime": null,
          "IsBind": null,
          "TotalScore": null,
          "TotalOrderCount": null,
          "IsSelected": null
        },
        "ProductCategory": {
          "PkId": "acea2081-1781-7c21-a14c-68b929110814",
          "Name": "冰箱",
          "SystemNumber": null,
          "NameIcon": null,
          "Sort": null,
          "ProductBrand": null,
          "ProductType": null,
          "CreateTime": null,
          "UpdateTime": null,
          "FaultList": null,
          "IsSelected": null,
          "TradePkId": "8bcc8f7f-1e52-f5b4-3ed3-3c4505adea4d",
          "ParentId": null,
          "ParentSubPkId": null,
          "ProductInfo": null,
          "IsSystemHas": null,
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
        "ProductModel": [
          {
            "PkId": null,
            "Name": null,
            "CreateTime": null,
            "FkSpecificationPkId": null,
            "SpecificationName": null
          }
        ],
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
        "IsSystemHas": null,
        "SystemNumber": null,
        "ParentId": null,
        "MaintenanceCycle": null,
        "OwnerProductInfoPkId": null,
        "CategoryTitlePic": null,
        "SystemSpecificationPkId": null
      },
      "MasterProductInfo": null,
      "FeedBack": null,
      "CreateTime": "2017-07-05 10:58:49",
      "TradeChannel": {
        "PkId": "63edd678-c0b5-ff3d-fa73-3ce2735c2010",
        "Name": "品牌商提�超级售后",
        "TradePkId": "8bcc8f7f-1e52-f5b4-3ed3-3c4505adea4d",
        "IsBranch": null
      },
      "OverlayBranch": null,
      "BranchInfo": {
        "SerialNumber": null,
        "PkId": "ad546cb8-aac1-4bd0-8f4b-162bdfc9946f",
        "UserName": "安徽美菱空调网点",
        "Name": "安徽美菱空调网点",
        "ShopName": "安徽美菱空调网点",
        "BranchAddress": null,
        "BranchTel": null,
        "BranchIcon": "http://oss.surdata.com/cs/common/636386602455698078.jpg",
        "BranchProvice": null,
        "BranchCity": null,
        "BranchArea": null,
        "BranchProviceId": null,
        "BranchCityId": null,
        "BranchAreaId": null,
        "Password": null,
        "Contact": {
          "TradePkId": null,
          "Province": null,
          "ProvinceId": null,
          "City": null,
          "CityId": null,
          "Area": null,
          "AreaId": null,
          "AddInfo": null,
          "Name": "宋小�,
          "Mobile": "17088888888",
          "Telephone": null,
          "Lng": null,
          "Lat": null,
          "Sex": null
        },
        "AuthServiceRegions": null,
        "AuthProductCates": null,
        "AuthServiceTypes": null,
        "LastDaysTradeCount": null,
        "TotalTradeCount": null,
        "TotalScore": null,
        "GoodRate": null,
        "BadRate": null,
        "IsCollection": null,
        "RelationStatus": null,
        "CooperationStatus": null,
        "CooperationMethod": null,
        "MasterCount": null,
        "BranchStatus": null,
        "EvaluationCount": null,
        "Remark": null,
        "CancelReason": null,
        "CancelTime": null,
        "CancelCooperReason": null,
        "CancelCooperTime": null,
        "RefuseReason": null,
        "RefuseTime": null,
        "RejectReason": null,
        "RejectTime": null,
        "JoinTime": null,
        "CreateTime": "2017-03-15 15:55:30",
        "BranchIdenCode": "BR636251901307327883",
        "DataFrom": null,
        "ServiceTypePkId": "00000000-0000-0000-0000-000000000000",
        "ServiceRange": null,
        "FaultMsg": null,
        "Sort": null,
        "CreateBrandsSellerPkId": null,
        "IsBrandsCreate": null,
        "CompanyImage": null,
        "RegisterFrom": "网点自注�,
        "BankInfo": null,
        "EstimatedMile": null,
        "EstimatedTrafficFee": null,
        "OrderVerName": null,
        "BranchIndustry": null,
        "OrderExpireDate": null,
        "IsEnabledSpareParts": false,
        "FlowSource": null
      },
      "Payment": null,
      "ReserveTime": "2017-07-05 10:58:00",
      "MasterReserveTime": null,
      "MasterReserveStatus": null,
      "ConfirmHome": {
        "TradePkId": "8bcc8f7f-1e52-f5b4-3ed3-3c4505adea4d",
        "HomeTime": null,
        "Lng": null,
        "Lat": null,
        "AddressInfo": null,
        "TradeOrder": null,
        "ComfirmHomeStatus": null
      },
      "IsSwap": null,
      "EvaluateStat": null,
      "EvaluateReason": 0,
      "BuyerInfo": {
        "PkId": "5327a292-1688-4974-b2d0-ef288d6cc1fa",
        "UserName": "13333333333",
        "LoginTime": "2017-09-20 11:57:10",
        "ProductCount": 14,
        "TradeCount": 1,
        "ServiceCount": 1,
        "LastTradeTime": "2017-08-26 15:52:07",
        "Name": null,
        "Mobile": "13333333333",
        "Address": null,
        "DetailAddress": null,
        "CreateTime": null,
        "ProductMaintenanceCount": null,
        "ProductChangeCount": null
      },
      "Contact": {
        "TradePkId": "8bcc8f7f-1e52-f5b4-3ed3-3c4505adea4d",
        "Province": "天津",
        "ProvinceId": 120000,
        "City": "天津�,
        "CityId": 120100,
        "Area": "河北�,
        "AreaId": 120105,
        "AddInfo": "不说",
        "Name": "皮卡丘不想动",
        "Mobile": "13333333333",
        "Telephone": null,
        "Lng": null,
        "Lat": null,
        "Sex": null
      },
      "TradeStatus": {
        "PkId": "30c723c0-dd69-1bc6-dd4a-bf2bae5e00f9",
        "Name": "等待师傅预约",
        "Sort": null,
        "Cate": null
      },
      "ServiceStatus": "等待师傅预约",
      "EvaCount": null,
      "GuaranteeInfo": {
        "TradePkId": "8bcc8f7f-1e52-f5b4-3ed3-3c4505adea4d",
        "PkId": "20f32225-1e8e-8800-e7cd-17ca56951a0d",
        "Name": "保内"
      },
      "IsGuarantee": null,
      "CloseReason": {
        "ReasonId": "00000000-0000-0000-0000-000000000000",
        "ReasonName": null
      },
      "CancelTime": null,
      "FormatTime": null,
      "BrandsSellerInfo": null,
      "BranchSellerInfo": null,
      "IsConfirm": null,
      "BranchName": "安徽美菱空调网点",
      "IsHasBranch": true,
      "ReMark": null,
      "MasterInfo": {
        "TradePkId": "8bcc8f7f-1e52-f5b4-3ed3-3c4505adea4d",
        "PkId": "bdd7f6c3-2d05-4bdf-8be5-557be2753e46",
        "UserName": "13122233345",
        "SellerInfo": null,
        "BranchInfo": null,
        "FullName": "王师�,
        "Mobile": "13122233345",
        "Password": null,
        "Avatar": null,
        "BaseSalary": null,
        "ServiceScore": null,
        "WorkStatus": null,
        "WorkSatausIcon": null,
        "MaxTradeCount": null,
        "TradeCount": null,
        "TradeTotalCount": null,
        "AlreadyPay": null,
        "SurplusCount": null,
        "Percentage": null,
        "CommissionRule": null,
        "ServiceTypes": null,
        "ProduceList": null,
        "HerderStr": null,
        "IsSendMobileMsg": null,
        "PassportPositive": null,
        "PassportNegative": null,
        "RegisterFrom": null,
        "AuditStatus": null,
        "CreateTime": null,
        "IsBound": null,
        "BranchName": null,
        "ServiceRange": null,
        "ServiceRangeList": null,
        "StartLevel": null,
        "ApprovalStatus": null,
        "IsSelected": null,
        "RefusedReason": null,
        "ServiceEndTradeCount": null,
        "WaitAppointTradeCount": null,
        "WaitServiceTradeCount": null,
        "Sort": null,
        "Passport": null,
        "PassportCode": null,
        "FkCommissionRulePkId": null,
        "BankInfo": null,
        "FkBranchSellerPkId": null,
        "DeviceId": null,
        "DeviceInfo": null,
        "VoiceBroadcast": null,
        "ServiceRegions": null,
        "ApprovalTime": null,
        "FisrtLoginTime": null,
        "WxUserOpenId": null,
        "WxUnionId": null,
        "WxHeadImgUrl": null,
        "WxNickName": null,
        "FlowSource": null,
        "Province": null,
        "City": null,
        "ProvinceId": null,
        "CityId": null,
        "AreaId": null,
        "Area": null,
        "AddressInfo": null,
        "RefusedTime": null,
        "RefusedUserName": null
      },
      "Pattern": null,
      "BadReviewTime": null,
      "CheckWorkStatus": null,
      "RightTopTime": null,
      "InLeftTime": null,
      "InRightTime": null,
      "TradeIconName": null,
      "ProductModel": {
        "PkId": null,
        "Name": null,
        "CreateTime": null,
        "FkSpecificationPkId": null,
        "SpecificationName": null
      },
      "SerialNumber": null,
      "BuyTime": null,
      "FwContent": null,
      "ExceptionType": null,
      "IsNowDate": null,
      "MorningAfternoon": null,
      "SubmitPriceTime": null,
      "ServicePriceList": null,
      "EvalList": null,
      "TradeServicePrice": null,
      "IsExistEval": null,
      "FkBrandsSellerPkId": "72030fd5-2628-4303-bbcb-30898207b52a",
      "IsCompleteVisit": null,
      "VisitFeedBackList": null,
      "ServiceImageList": [

      ],
      "IsExistComplaints": null,
      "IsSmsVisit": null,
      "IsWeixinVisit": null,
      "ComplaintsIsEnd": null,
      "IsExistReminder": null,
      "ReminderIsEnd": null,
      "IsUrgentProcess": null,
      "ComplaintsList": null,
      "TradeProductServiceRemind": null,
      "RegionAgentInfo": null,
      "DelayProcessStatus": null,
      "BadReviewProcessStatus": null,
      "FkSourceTradePkId": null,
      "FkSouceBrandsSellerPkId": null,
      "SouceBrandsShopName": null,
      "IsDockingTrade": null,
      "FkDockingShopPkId": null,
      "FkDockingTradePkId": null,
      "ReserveNoon": null,
      "TradeFinance": null,
      "TradeServiceMethod": null,
      "TradeProductBrand": {
        "TradePkId": "8bcc8f7f-1e52-f5b4-3ed3-3c4505adea4d",
        "PkId": "d12c1c1c-ebd5-893f-9d4a-1b801c219524",
        "Name": "测试品牌"
      },
      "TradeSparePartList": null,
      "FaultType": null,
      "DockingShopName": null,
      "IsGuaranteeCreated": null,
      "OriginalCreateTime": null,
      "EndVisitedTime": null,
      "DispatchBranchTime": null,
      "MasterReserveOptTime": null,
      "BranchEndServiceTime": null,
      "TradeProductSpecification": null,
      "IsReject": null,
      "SettlerPkId": null,
      "SettlerName": null,
      "SettleTime": null,
      "BranchDispatchMasterOptTime": null,
      "IsReassigned": null,
      "RejectTime": null,
      "RejectStatus": null,
      "RejectRecordList": null,
      "RejectProcessRecordList": null,
      "TradeCount": null,
      "FkBranchSellerPkId": "ad546cb8-aac1-4bd0-8f4b-162bdfc9946f",
      "BranchSellerName": null,
      "SendTradeBranchType": null,
      "FkBrandsSubUserPkId": null,
      "BuyChannel": null,
      "FkDispatchKefuUserPkId": null,
      "ReservDelayStatus": null,
      "DoorDelayStatus": null,
      "ServiceDelayStatus": null,
      "CallSeat": null,
      "IsReservDelayOrder": null,
      "IsDoorDelayOrder": null,
      "IsServiceDelayOrder": null,
      "QualityIdentyStatus": null,
      "QualityIdentyInfo": null,
      "FkCallingPkId": null
    },
     ...
  ],
  "total": null
}
```

## 返回结果说明 {#返回结果说明}

| 返回字段 | 字段类型 | 字段说明 |
| :--- | :--- | :--- |
| PageIndex | int | 当前页码 |
| PageSize | int | 每页条数 |
| PageCount | int | 总页�|
| DataRows | List&lt;TradeInfo&gt; | 订单数据列表 |
| DataCount | int | 数据总条目数 |
| DataName | string | 数据记录名称 |
| DateDesc | string | 数据描述，暂未使�|
| IsSelect | bool | 是否选中，暂未使�|
| MasterNormalCardCount | int | 师傅正常打卡次数，暂未使�|
| MasterLateCardCount | int | 师傅迟到打卡次数，暂未使�|
| MasterMissCardCount | int | 师傅缺勤打卡次数，暂未使�|
| MasterOutCardCount | int | 师傅外勤打卡次数，暂未使�|
| IsNowDate | bool | 是否当前日期，暂未使�|
| MasterName | string | 师傅姓名，暂未使�|
| total | int | 同DataCount，暂未使�|

TradeInfo（订单）返回字段说明

| 返回字段 | 字段类型 | 字段说明 |
| :--- | :--- | :--- |
| PkId | Guid | 订单主键 |
| TradeId | string | 唯一订单编号 |
| TradeNo | string | 订单流水�|
| ServiceType | Object | 订单服务类型，参见服务类型相关API |
| ProductInfo | Object | 产品品类，参见产品品类相关API |
| MasterProductInfo | Object | 师傅的产品信息，暂未使用 |
| FeedBack | string | 反馈情况 |
| CreateTime | DateTime | 订单创建时间 |
| TradeChnnel | Object | 订单来源 |
| OverlayBranch | Object | 覆盖网点 |
| BranchInfo | Object | 派单网点 |
| Payment | deciaml | 订单总额 |
| ReserveTime | DateTime | 预约时间 |
| MasterReserveStatus | string | 师傅预约状�|
| ConfirmHome | Object | 确认上门 |
| IsSwap | bool | 是否可改�|
| EvaluateStat | int | 评价星数 |
| EvaluateReason | int | 评价里有 |
| BuyerInfo | Object | 下单用户信息 |
| Contact | Object | 订单联系人信�|
| TradeStatus | Object | 订单服务状态信�|
| ServiceStatus | string | 订单服务状�|
| IsGuarantee | bool | 是否保修期内 |
| CloseReason | Object | 订单取消原因 |
| CancelTime | DateTime | 订单取消时间 |
| FormatTime | DateTime | 格式化时间，暂未使用 |
| BrandsSellerInfo | Object | 品牌商用户信�|
| BranchSellerInfo | Object | 网点商用户信�|
| IsConfirm | bool | 是否确认上门 |
| BranchName | string | 网点名称 |
| IsHasBranch | bool | 是否已达网点 |
| ReMark | string | 服务兵端服务备注 |
| MasterInfo | Object | 师傅信息 |
| Pattern | string | 派单模式 |
| BadReviewTime | DateTime | 差评时间 |
| CheckWorkStatus | Object | 师傅考勤信息，暂未使�|
| RightTopTime | string |  |
| InLeftTime | string |  |
| InRightTime | string |  |
| TradeIconName | string |  |
| ProductModel | Object | 工单产品型号 |
| SerialNumber | string | 服务兵端-产品序列�|
| BuyTime | DateTime | 服务兵端-购买时间 |
| FwContent | string | 服务兵端-服务内容描述 |
| ExceptionType | string | 异常订单来源类型 |
| IsNowDate | bool | 是否当前日期 |
| MorningAfternoon | string | 上午/下午 |
| SubmitPriceTime | DateTime | 提交报价时间 |
| ServicePriceList | List&lt;Object&gt; | 服务报价列表 |
| EvalList | List&lt;Object&gt; | 评论内容 |
| TradeServicePrice | Object | 订单报价金额信息 |
| IsExistEval | bool | 订单是否存在报价 |
| FkBrandsSellerPkId | Guid | 外键品牌商Id |
| IsCompleteVisit | bool | 是否已回�|
| VisitFeedBackList | List&lt;Object&gt; | 回访�回访反馈记录 |
| ServiceImageList | List&lt;Object&gt; | 服务照片�|
| IsExistComplaints | bool | 是否存在订单投诉 |
| IsSmsVisit | bool | 是否已短信回�|
| IsWeixinVisit | bool | 是否已微信回�|
| ComplaintsIsEnd | bool | 投诉处理是否完成 |
| IsExistReminder | bool | 是否存在催单 |
| ReminderIsEnd | bool | 催单是否完成 |
| IsUrgentProcess | bool | 是否加急处�|
| ComplaintsList | List&lt;Object&gt; | 投诉记录 |
| TradeProductServiceRemind | Object | 订单产品服务备注 |
| RegionAgentInfo | Object | 区域代理商信�|
| DelayProcessStatus | string | 延期处理状�|
| BadReviewProcessStatus | string | 差评处理状�|
| FkSourceTradePkId | Guid | 原订单编�|
| FkSouceBrandsSellerPkId | Guid | 原订单品牌商编号 |
| SouceBrandsShopName | string | 原订单品牌商名称 |
| IsDockingTrade | bool | 是否已成为联保商订单 |
| FkDockingShopPkId | Guid | 联保商ID |
| FkDockingTradePkId | Guid | 联保商订单编�|
| ReserveNoon | string | 预约时间：上午、中午、下�|
| TradeFinance | Object | 订单相关金额 |
| TradeServiceMethod | Object | 订单服务措施 |
| TradeProductBrand | Object | 订单产品品牌 |
| TradeSparePartList | List&lt;Object&gt; | 备件明细列表 |
| FaultType | string | 故障类型（维修订单时需要） |
| DockingShopName | string | 订单指派联保-联保商名�|
| IsGuaranteeCreated | bool | 是否联保商自营订�|
| OriginalCreateTime | DateTime | 原始订单下单时间 |
| EndVisitedTime | DateTime | 回访完成时间 |
| DispatchBranchTime | DateTime | 派单到网点的时间 |
| MasterReserveOptTime | DateTime | 师傅预约操作的时�|
| BranchEndServiceTime | DateTime | 网点完成服务的时�|
| TradeProductSpecification | Object | 产品规格 |
| IsReject | bool | 是否驳回 |
| SettlerPkId | Guid | 结算人编�|
| SettlerName | string | 结算人名�|
| SettleTime | DateTime | 结算时间 |
| BranchDispatchMasterOptTime | DateTime | 网点派单到师傅的操作时间 |
| IsReassigned | bool | 是否改派 |
| RejectTime | DateTime | 驳回时间 |
| RejectStatus | string | 驳回状�|
| RejectRecordList | List&lt;Object&gt; | 驳回记录列表 |
| RejectProcessRecordList | List&lt;Object&gt; | 驳回进度记录列表 |
| TradeCount | int | 订单数量，暂未启�|
| FkBranchSellerPkId | Guid | 所属网点ID |
| BranchSellerName | string | 所属网点名�|
| SendTradeBranchType | strinig | 派单类型：联保商、合作网�|
| FkBrandsSubUserPkId | Guid | 品牌商子账号用户ID |
| BuyChannel | string | 购买渠道 |
| FkDispatchKefuUserPkId | Guid | 客服分单用户编号 |
| ReservDelayStatus | string | 预约延期处理状�|
| DoorDelayStatus | string | 上门延期处理状�|
| ServiceDelayStatus | string | 服务延时处理状�|
| CallSeat | int | 呼叫坐席 |
| IsReservDelayOrder | bool | 是否预约延时 |
| IsDoorDelayOrder | bool | 是否上门延时 |
| IsServiceDelayOrder | bool | 是否服务延时 |
| QualityIdentyStatus | string | 质量鉴定状�|
| QualityIdentyInfo | Object | 质量鉴定信息 |
| FkCallingPkId | Guid | 呼叫通话编码 |
| BrandsSellerName | string | 品牌商用户名�|

TradeChannel（订单来源）字段说明

| 返回字段 | 字段类型 | 字段说明 |
| :--- | :--- | :--- |
| PkId | Guid | 订单来源ID |
| Name | string | 订单来源名称 |
| TradePkId | Guid | 订单PkId |
| IsBranch | bool | 是否网点 |

Contact \(联系人信息\) 字段说明

| 字段说明 | 字段类型 | 字段说明 |
| :--- | :--- | :--- |
| TradePkId | Guid | 所属订单ID |
| Province | string | 省份 |
| ProvinceId | int | 省份id |
| City | string | 城市 |
| CityId | int | 城市id |
| Area | string | 地区 |
| AreaId | int | 地区id |
| AddInfo | string | 地址 |
| Name | string | 联系人姓�|
| Mobile | string | 手机 |
| Telephone | string | 联系电话 |
| Lng | decimal | 经度 |
| Lat | decimal | 维度 |
| Sex | string | 性别 |

BranchInfo （网点） 返回字段说明

| 返回字段 | 字段类型 | 字段说明 |
| :--- | :--- | :--- |
| SerialNumber | int | 序号 |
| PkId | Guid | 主键PkId |
| UserName | string | 登录用户�|
| Name | string | 网点名称 |
| ShopName | string | 网点名称\(跟品牌商的统一,旧的也兼容\) |
| BranchAddress | string | 网店地址 |
| BranchTel | string | 网点联系手机�|
| BranchIcon | string | 网点图标 |
| BranchProvice | string | 网点�|
| BranchCity | string | 网点�|
| BranchArea | string | 网点区域 |
| BranchProviceId | int | 省Id |
| BranchCityId | int | 市Id |
| BranchAreaId | int | 区Id |
| Password | string | 登录密码 |
| Contact | Object | 参考联系人信息字段说明 |
| AuthServiceRegions | List&lt;Object&gt; | 授权服务区域，暂未使�|
| AuthProductCates | List&lt;Object&gt; | 授权产品线，暂未使用 |
| AuthServiceTypes | List&lt;Object&gt; | 服务类型，暂未使�|
| LastDaysTradeCount | int | 最�0天订单数 |
| TotalTradeCount | int | 总单�|
| TotalScore | decimal | 综合评分 |
| GoodRate | decimal | 好评�|
| BadRate | decimal | 差评�|
| IsCollection | bool | 是否收藏 |
| RelationStatus | string | 关联状�|
| CooperationStatus | string | 合作状�|
| CooperationMethod | string | 合作方式 |
| MasterCount | int | 拥有师傅数量 |
| BranchStatus | string | 当前状�|
| EvaluationCount | int | 评论数量 |
| Remark | string | 备注 |
| CancelReason | string | 取消关联原因 |
| CancelTime | DateTime | 取消时间 |
| CancelCooperReason | string | 取消合作原因 |
| CancelCooperTime | string | 取消合作时间 |
| RefuseReason | string | 拒绝原因 |
| RefuseTime | DateTime | 拒绝时间 |
| RefuseTime | string | 驳回原因 |
| RejectReason | DateTime | 驳回时间 |
| JoinTime | DateTime | 入住时间 |
| CreateTime | DateTime | 创建时间 |
| BranchIdenCode | string | 网点识别�|
| DataFrom | string | 数据来源 |
| ServiceTypePkId | Guid | 添加网点时服务类�|
| ServiceRange | List&lt;Object&gt; | 授权产品�|
| FaultMsg | string | 导入的返回状�|
| Sort | int | 排序 |
| CreateBrandsSellerPkId | Guid | 添加品牌商UserId |
| IsBranchCreate | bool | 是否网点创建 |
| CompanyImage | string | 公司图片 |
| RegisterFrom | string | 注册来源 |
| BankInfo | List&lt;Object&gt; | 银行卡信息，暂未使用 |
| EstimatedMile | decimal | 预计里程 
| EstimatedTrafficFee | decimal | 预计交通费�
| OrderVerName | string | 订购的版本名�|
| BranchIndustry | string | 行业 |
| OrderExpireDate | DateTime | 订购到期时间 |
| IsEnabledSpareParts | bool | 管理备件是否启用 |
| FlowSource | string | 流量来源 |
| IsServiceCenter | bool | 是否服务中心 |