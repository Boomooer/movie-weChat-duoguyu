#### 《多骨鱼·楽间 电影排行榜》微信小程序 v1.2.0 快速开发 Demo

  > 线上实例， 请使用微信小程序搜索：多骨鱼；
  > 由于时间及项目原因，当前项目难免有部分bug和待完善的地方，欢迎拍砖和指点交流；
  > 该Demo代码仅为入门小程序参考使用。

  本仓库是简版的《多骨鱼·楽间 电影排行榜》微信小程序Demo，后端数据使用YZMCMS开源管理程序提供的API。
  仅供学习交流使用，
  该小程序提供搜索、收藏、菜单列表、内容视图等功能，部分功能是使用本地数据存储(收藏)。
  如需使用该实例中提供的API，请在 “微信公众平台 | 小程序” 后台 -> 设置 -> 开发设置 -> 服务器域名 中，将 https://demo.duoguyu.com 加入到服务器域名列表内
  
  部分可提供API接口如下（也可以在根目录下 -> client -> dgyApi -> dgyApi.js 中获取详细API接口信息）：
  > **注意：**
  >
  > 由于本人服务器属于个人项目使用，如遇到请求失败或不响应，请稍后重试；
  > 你也可以直接进我们的QQ群进行交流（YZMCMS交流群：161208398）。

  1. 导航
    url: https://demo.duoguyu.com/index/api/nav

  2. 内容详情
    url: https://demo.duoguyu.com/index/api/content
    data:{ 
      "modelid":"1", // 模型类型
      "id":"1", // 内容id
    }

  3. banner
    url: https://demo.duoguyu.com/index/api/banner

  4. TAG标签
    url: https://demo.duoguyu.com/index/api/tag

  5. 标签搜索
    url: https://demo.duoguyu.com/index/api/tag_search

  6. 列表页、通用搜索
    url： https://demo.duoguyu.com/index/api
    data:{ 
      "modelid":"1", // 模型类型
      "id":"1", // 内容id
      "catid":"8", // 栏目id
      "q":"名称", // 搜索名称
      "flag": "2", // 内容属性：置顶、头条、特荐、推荐、热点、幻灯、跳转
    }

#### 其它说明

1. 程序支持 - YZMCMS（优秀的轻量级开源管理系统）
  - http://www.yzmcms.com（官网）
  - http://blog.yzmcms.com（袁志蒙技术博客）
  - http://bbs.yzmcms.com（YZMCMS论坛）

2. 关于我
  - tonney@duoguyu.com（E-mail）
  - http://www.duoguyu.com（个人网站）
  - http://blog.duoguyu.com（个人博客）
  - VinosToby（微信）

#### 后续迭代升级
  
  后续升级迭代计划及相关补丁，请关注微信小程序搜索：多骨鱼。

#### 小程序 - 二维码
![image](http://www.duoguyu.com/dist/weChat/gh_07f5145fa318_258.jpg)
  
  
