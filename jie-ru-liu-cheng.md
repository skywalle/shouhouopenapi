# 接入说明

针对超级售后的品牌商系统用户!目前开放API实现订单推送的功能,后期会开放更多接口出来

# 接入地址

1.token调用地址http://apigate.51shouhou.cn/token
2.get调用地址http://apigate.51shouhou.cn/getinfo/{userId}
3.post调用地http://apigate.51shouhou.cn/postinfo/{userId}

# 接入流程

1.品牌商主账号  
2.调用[http://apigate.51shouhou.cn/token获取授权token](http://apigate.51shouhou.cn/token获取授权token)  
3.http请求头增加Key为Authorization值为Bearer加上空格附加token里面access\_token  
4.存储token钟的PkId为userId调用api

# 



