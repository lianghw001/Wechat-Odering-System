## 学习报告之前端实现

**学号：18214630    姓名：胡晋荣**

### 1. 微信小程序实现技术

为了进行微信小程序的前端实现，我查阅了腾讯官方的文档，使用官方的开发工具，在其中找到了一些实例小程序进行研究，对小程序的开发有了一些见解，以下是我认为的一些特点。

* **基于网页**：微信小程序基于网页技术，有着与网页的HTML, CSS, JavaScript相似的构成元素：wxml, wcss, js, json，但是api与浏览器不一样，读取渲染的逻辑也略有不同。然而一个网页前端工程师仍然能较快地上手。
* **安全受控**：微信对于微信小程序的权限有着严格控制，对于用户只能获取昵称、头像等公开信息，以及一个只在小程序用到的openid。访问网络也只能访问小程序报备的域名，并且强制要求https。
* **响应式布局**：小程序面向的是各种各样不同屏幕大小的手机或平板，它的布局设计天然要求了要对至少绝大部分的屏幕大小有好的兼容。


学习材料：

1. https://developers.weixin.qq.com/miniprogram/dev/



### 2. 由需求到原型

* 本项目目前完成的是手机端：面向客户的点餐小程序。由于功能较为简单，直接从需求文档与UI设计入手，制作出对应的小程序原型。


* 使用工具：使用腾讯官方的开发工具`微信web开发者工具`， 该工具可以方便地进行小程序的 API 和页面的开发调试、代码查看和编辑、小程序预览和发布等功能。


* 对于使用微信小程序开发的客户端界面，首先学习微信小程序官方文档中的开发指南，确定合适的布局方式以及脚本逻辑。




### 3. 小程序开发过程

第一轮迭代中的客户端界面主要分为三个部分：

* 点餐程序主页面的开发
* 菜单界面的布局与脚本逻辑的开发
* 点击某个单品，出现饮品的详情界面

第二轮迭代中的客户端界面主要分为六个部分：

* 选择菜品后购物车显示状态
* 点击支付按钮，出现订单界面
* 完成支付，订单状态为等待取餐
* 取餐完成，订单交易状态为完成
* 点击查看历史订单按钮，出现历史订单界面

第三轮迭代中的客户端界面主要分为两个部分：

* 点击某个单品，出现饮品的评价列表
* 调整界面设计



