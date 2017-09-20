# 接入说明

针对超级售后的品牌商系统用户!目前开放API实现订单推送的功能,后期会开放更多接口出来

# 接入地址

1.token调用地址[http://apigate.51shouhou.cn/token](http://apigate.51shouhou.cn/token)  
2.get调用地址[http://apigate.51shouhou.cn/getinfo/{userId}](http://apigate.51shouhou.cn/getinfo/{userId})  
3.post调用地[http://apigate.51shouhou.cn/postinfo/{userId}](http://apigate.51shouhou.cn/postinfo/{userId})

# 接入流程

流程图：

![](/assets/user-api-flow.png)

参数说明：

1、品牌商主账号，登录获取Token：http://apigate.51shouhou.cn/token?grant\_type=password&username={username}&password={password}；username：主账号，password：密码；

Token Example With Json：

```
{
    "access_token": "lCv***SXY",
    "token_type": "bearer",
    "expires_in": 1209599,
    "PkId": "ad5***46f",    /*用户Id*/
    "UserName": "安徽**空调",
    "RoleName": "网**组",
    "ContextUserName": "170***8888",
    ".issued": "Wed, 20 Sep 2017 07:10:48 GMT",
    ".expires": "Wed, 04 Oct 2017 07:10:48 GMT"
}
```

2、请求操作数据认证Http Header增加Key-Value：Authorization:Bearer {access\_token}

HTTP Request Header：

```
Authorization:Bearer lCv***SXY
```



