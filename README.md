# hospital

> 一个简单的医院预约挂号管理系统。包括 小程序、web管理系统、服务端

### 主要技术
- `Spring boot + Mybatis` ： 实现基于 `RESTful` 的前后端分离架构。
- `Spring Security + JWT` ： 实现基于角色的动态权限管理。
- `Mybatis generator` ： 逆向生成相关实体类与配置文件，并且添加了相关 Swagger 注释。
- `Knife4j` ： 基于 Swagger + bootstrap 的 API 文档工具。 
- `阿里云短信服务` : 实现短信发送功能。
- `七牛云文件存储服务`: 取代自建的FTP图片服务器，实现图片存储便宜稳定。
- `Lombok` ： 减少了冗余的 Getter / Setter 代码。
- `Redis` ：实现二级缓存，提高响应速度。

### 软件界面

#### 小程序

![image.png](http://image.yujian95.cn/halo/image_1643879798008.png)
![image.png](http://image.yujian95.cn/halo/image_1643879818766.png)
![image.png](http://image.yujian95.cn/halo/image_1643879835630.png)
- [更多小程序运行图片](https://github.com/YuJian95/Product-Prototype/tree/master/hospital-appointment#小程序)

#### 管理系统

![image.png](http://image.yujian95.cn/halo/image_1643879859752.png)
![image.png](http://image.yujian95.cn/halo/image_1643879874985.png)
![image.png](http://image.yujian95.cn/halo/image_1643879886827.png)

更多效果可点击查看[/doc/demo.md](doc/demo.md)

### 部署步骤

点击查看[/doc/deploy.md](doc/deploy.md)

