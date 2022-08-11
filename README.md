# 开发项目介绍 - 用于求职 v1.0

> 本文档用于求职，找到工作后关闭。。
>
> 如果图片不显示，记打开 readme.pdf

### CFD - 数字货币交易所

+ 技术选型

  > + 使用SpringCloudNetflix全家桶 ，使用SpringBoot开发服务
  > + 使用ReactNative做APP
  > + 使用Vue做管理后台
  > + 使用mysql做数据库，并且进行了分库分表设计
  > + 使用 xxl-job做定时任务
  > + 使用RocketMQ做消息队列
  > + Docker 进行容器化部署
  > + 使用阿里云整套运维解决方法(如: 负载均衡，DNS, CDN加速，ESC,RDS,OSS等。)

+ 业务架构

  <img src="Image/cfd-java整体架构图.png" style="zoom:40%;" />

+ 项目截图

<table><tr><td><img src="Image/cfd_db_1.png" style="zoom:50%;" /></td><td><img src="Image/cfd_db_2.png" style="zoom:50%;" /></td></tr></table>

<img src="Image/cfd 代码简图.png" style="zoom:50%;" />

<img src="Image/WX20220809-183429@2x.png" style="zoom:60%;" />

<img src="Image/1660041304601.jpg" style="zoom:25%;" />

<img src="Image/1660041190558.jpg" style="zoom:50%;" />

<img src="Image/WX20220809-183526@2x.png" style="zoom:50%;" />

+ 参与相关开源

> 了解一个开源的撮合引擎，并且帮助该引擎画出流程架构图，并被作者引用感谢（https://gitee.com/flying-cattle/match-trade），（PS:如果有必要，该作者可以给我署名，但由于后续不想从事该领域，所以在这方面就不希望得到过多的关注）
>
> <img src="Image/WX20220811-103959@2x.png" style="zoom:50%;" />
>
> <img src="Image/撮合代码解读.png" style="zoom:40%;" />

### Oasis-Shop（开源，暂未上传）

> 开源商城Saas项目
>
> + 设计特色功能
>   + 设计通用代码生成器，为项目生成百分之70左右的常用代码，提高开发效率，也减少出错。
>   + 产品通过消息队列异构到ES中，并提供多维度产品搜索
>   + 在客户做`埋点`，收集用户行为，为以后做数据分析使用

+ 技术选型(初步目标)

> + 使用springboot 开发服务
> + 使用SpringCloudAlibaba全家桶(Nocas,SpringCloudGateway,Setine,OpenFiegn等)
> + 使用SpringSeucrityOAuth做安全组件
> + 使用自有数据库访问组件(Oasis-DB)或使用MybatisPlus
> + 使用RocketMQ做消息队列
> + 使用XXL-job做定时任务
> + 使用OSS（Minio) 做文件存储
> + 使用Redis做缓存数据库
> + 使用MySql做数据库(分库分表支持)
> + 使用ES做产品搜索引擎(考虑使用Canal监听mysql，然后扔到消息队列后异构到ES中。)
> + 使用docker做服务容器
> + 使用Vue做管理后台
> + 使用Flutter做APP端
> + 使用UniAPP做小程序端
> + 使用Apifox 做文档、测试等

+ 技术架构

  <img src="image/SpringCloudAlibaba运维架构图.png" style="zoom:50%;" />

+ 业务设计(暂无)

+ 项目代码截图

<img src="Image/管理后台代码.png" style="zoom:50%;" />

<img src="Image/单服务结构.png" style="zoom:50%;" />

### Oasis-DB（开源）

> 数据库访问组件，与`Mybatis-Plus`作用相似

+ 组件演示

<img src="./Image/db_1.png" style="zoom:50%;" />

<img src="Image/db_2.png" style="zoom:50%;" />

<img src="Image/db_3.png" style="zoom:50%;" />

### 其他项目截图

+ 代码生成器

<img src="Image/WX20220801-144310@2x.png" style="zoom:50%;" />

<img src="Image/1659336196402.jpg" style="zoom:50%;" />

+ 某汽车经销商CRM

  <table>
    <tr>
    	<td><img src="Image/WX20220808-194422@2x.png" style="zoom:30%;" /></td>
      <td><img src="Image/WX20220808-194527@2x.png" style="zoom:30%;" /></td>
    </tr>
  </table>
  
  
+ 部分自定义UI组件(vue)

<img src="Image/SQL条件选择器.png" style="zoom:50%;" />

+ 某物流平台项目主流程初步分析图

  <img src="Image/61660189549_.pic.jpg" style="zoom:50%;" />

+ 

  

  

  

  

  

  
