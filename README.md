# JD-simulator
基于Python 3 京东商城模拟工具
第三方库依赖:
  requests
  BeautifulSoup
  lxml
  pickle
## 主要功能
模拟京东商城的两种登录请求、查询商品信息、修改购物车以及订单页面信息、提交订单、获取优惠券等服务
## 目前已实现功能
### class Login
> △验证码扫码登录 2018.2.6 </br> 
> △密码登录 2018.2.7 #bug : 无法无验证码登录 </br> 
>   保存cookies 2018.2.6 </br>
> ※验证cookies是否过期 2018.2.8 </br>
### class Purchase
>   查看商品库存 2018.2.6 </br>
>   查看商品价格 2018.2.6 </br>
>   添加商品进入购物车 2018.2.7 </br>
>   显示购物车信息 2018.2.6 </br>
> ※修改购物车功能 2018.2.8 </br>
>>  修改数量 + -  </br>
>>  修改选中 + -  </br>
>>※选择优惠  </br>
>>  删除商品  </br>

>   代码模块化 2018.2.7 </br>
## 程序入口
## API解析 类 函数
## 计划实现功能
> 提交订单 </br>
>>  优惠券选择  </br>
>>  地址选择  </br>
>>  支付密码、验证码输入  </br>
>>  
>   模拟 预售 抢购 等商品的定时购买 </br>
>   更友好的助手函数 </br>
> 
>   模拟获取优惠券功能  </br>

>   API文档填写  </br>
