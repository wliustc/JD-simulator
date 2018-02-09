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
#大部分功能已有思路, 但是搬砖太累,接下来可能会只更新自己用到的功能  
> 2.9 添加Plus专享价格信息  
> 2.9 全球购、普通商品隐藏bug发现  
> 2.9   
### class Login
> △验证码扫码登录 2018.2.6  
> △密码登录 2018.2.7 #bug : 无法无验证码登录   
>   保存cookies 2018.2.6  
> ※验证cookies是否过期 2018.2.8  
### class Purchase  
>   查看商品库存 2018.2.6  
>   查看商品价格 2018.2.6  
>   添加商品进入购物车 2018.2.7  
>   显示购物车信息 2018.2.6  
> ※修改购物车功能 2018.2.8  
>>  修改数量 + -   
>>  修改选中 + -  
>>※选择优惠  
>>  删除商品  

>   代码模块化 2018.2.7  
## 程序入口  
## API解析 类 函数  
## 计划实现功能  
> 提交订单  
>>  优惠券选择  
>>  地址选择  
>>  支付密码、验证码输入  
>>  
>   模拟 预售 抢购 等商品的定时购买  
>   更友好的助手函数  
> 
>   模拟获取优惠券功能  

>   API文档填写  
