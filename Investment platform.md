# 项目说明
## 一个投资平台
## 会员身份为融资人或投资人（不能有两种身份），
## 融资人可以发出融资申请，后台通过后，前端能获取到该融资项目，
## 投资人可以进行投资，投满后，生成还款计划，融资人按月还款，全部还完则项目结束。

# 模块划分
## 1、登陆模块 
## 2、注册模块
## 3、首页
## 4、会员中心（充值 提现 我的投资 我的借款 个人资料等）
## 5、投资模块（包含借款申请、标的列表、标的详情、投资、还款计划、还款）
## 6、公告
## 由于没有后台配合，准备用express搭建一个服务器，模拟前后端交互。

# 准备知识
## 1、Vue
## 2、flex
## 3、less
## 4、本地存储(用来保存登录用户个人信息 ，token ，数据字典)
## 5、Http协议
## 6、跨域解决方案
## 7、路由守卫（路由跳转前做一些验证，比如登录验证、身份验证，融资人不能进入我的投资，投资人不能进入我的借款）
## 8、express