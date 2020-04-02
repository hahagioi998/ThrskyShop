⚠️注意点:这个项目只包含后端，并没有前端页面，而且是根据慕课网的项目改编而来，其中的很多设计和框架，在如今看来都已经有点过时，请酌情参考


# 在线购物平台 
## 核心框架基于SSM、集成支付宝接口


### 学习心得：
>* 要导入mybatis-generator：   
   在pom.xml - build - plugins - plugin中导入**mybatis-generator-maven-plugin**即可
   
>* mybatis-generator的配置文件是generatorConfig.xml，里面有完整的注释，这里就不多讲了

>* datasource.properties 中配置mysql.jar包时需要用绝对路径，如果有人要直接copy我的代码的话请修改路径

>* 在mapper文件中 对createTime 和  updateTime 时间戳进行更新 用db的语法来控制，不用Java的语法

## 安全问题
>* 横向越权和纵向越权
>* md5加密


## 接口设计
### 首页-用户接口
>* 登录
>* 注册
>* 检查用户是否有效
>* 获取登录状态信息
>* 忘记密码
>* 提交问题答案
>* 忘记密码的重设密码
>* 登录状态 重置密码
>* 登录状态更新个人信息
>* 获取当前登录用户的详细信息，并强制登录
>* 退出登录

### 后台用户接口
>* 后台管理员登录

### 后台-产品接口
>* 产品列表
>* 产品搜索
>* 图片上传
>* 产品详情
>* 产品上下架
>* 新增OR更新产品
>* 富文本上传图片

### 后台-品类接口
>* 获取品类子节点
>* 增加节点
>* 修改品类名字
>* 获取当前分类ID及递归子节点categoryID

### 后台-订单接口
>* 订单列表
>* 按订单号查询
>* 订单详情
>* 订单发货

### 首页-产品接口
>* 产品搜索及动态排序列表
>* 产品详细信息

### 首页-支付接口
>* 支付
>* 查询订单支付状态
>* 支付宝回调

### 首页-收获地址接口
>* 添加地址
>* 删除地址
>* 登录状态更新地址
>* 选中查看具体的地址
>* 地址列表

### 首页-订单接口
>* 创建订单
>* 创建订单的商品信息
>* 订单列表
>* 订单详情
>* 取消订单

### 首页-购物车接口
>* 购物车列表
>* 购物车添加商品
>* 更新购物车中某个商品的数量
>* 移除购物车中某个商品
>* 购物车中取消选取某个商品
>* 查询在购物车里的产品数量
>* 购物车全选
>* 购物车取消全选

<head> 
    <script defer src="https://use.fontawesome.com/releases/v5.0.13/js/all.js"></script> 
    <script defer src="https://use.fontawesome.com/releases/v5.0.13/js/v4-shims.js"></script> 
</head> 
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.13/css/all.css">
