# Treasure-Box

## 需求调研

1. 个人的博客项目，提供博客中的所有基础功能
2. 可拓展的百宝箱，将个人学习的知识和项目整合到一起
3. 后台管理系统，对于项目内容都做好管理，除了基础的项目管理，还需要后台的博客管理系统



## 需求分析

### 一、博客

#### 博客展示页

| 功能模块         | 子功能                   | 功能描述                                                     |
| ---------------- | ------------------------ | ------------------------------------------------------------ |
| 博客信息展示     | 展示大体信息             | 在页面右侧有常驻导航栏，展示普通信息，如果点开了博客详情页，则展示文章目录<br />普通信息包括：一些想说的话，一些个人简介 |
| 博客列表展示     | 展示所有博客信息，并分页 | 将存储的博客信息用简要信息进行展示，并做好分页               |
|                  | 单个博客信息展示         | 单个博客信息需要包含 标题、简介、缩略图、发布时间、作者、词数、阅读时间、点赞数、评论数、标签 |
| 博客详细信息展示 | 博客信息展示             | 使用markdown语法进行展示，页眉包含信息：发布时间、作者、词数、阅读时间、点赞数、评论数、标签、浏览量<br />页脚包含信息：本文链接+版权声明，作者介绍框，评论板块 |
|                  | 作者信息展示             | 包含作者头像、作者名称、作者个性签名、作者简介、作者发文数量 |
|                  | 上一篇下一篇文章跳转     | 需要两个按钮来实现上一篇文章和下一篇文章的快速跳转，需要包含：作者信息、文章名称 |
| 博客列表页眉页脚 | 展示每日一句             | 获取每日一句信息并展示在页眉                                 |
|                  | 展示当前存档的文章数量   | 展示文档数量                                                 |



#### 第三方登录接口接入

| 功能模块       | 子功能               | 功能描述                                         |
| -------------- | -------------------- | ------------------------------------------------ |
| GitHub评论功能 | GitHub登录功能       | 接入GitHub第三方登录接口，可以获取到相关个人信息 |
|                | GitHub评论功能       | 接入第三方接口，用户可以对博客进行评论           |
| 第三方登录     | QQ、微信、GitHub登录 |                                                  |



### 二、百宝箱

秒杀



搜索



定时任务



聊天室



消息队列



excel操作



支付操作



### 三、后台管理

目录管理(root权限)



权限管理(root权限)



用户管理(root权限)



文章管理



文章撰写







四、杂项