#接入说明
针对超级售后的品牌商系统用户!目前开放API实现订单推送的功能,后期会开放更多接口出来
#接入前期准备
1.品牌商主账号
2.调用http://apigate.51shouhou.cn/token获取授权token
3.附加token里面access_token到http请求头增加Key为Authorization值为Bearer加上空格加上toekn
#接入流程