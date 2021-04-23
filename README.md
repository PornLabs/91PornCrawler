# 91Porn Crawler | 91Porn 采集器  | 91Porn 爬虫  

最新的91Porn 采集工具 ,91Porn爬虫,91Porn采集器,91Porn Spider   
暂未开源,纯属技术研究  
   
欢迎大家参与讨论 [GITHUB 讨论 Discussions](https://github.com/chinaporn/91PornCrawler/discussions)     
   
## 系统架构  
  采集器分的架构介绍 
  
- Master 类似与是主控，负责调度  
- Node 可以理解为节点，但是这个节点默认由Master进行调度的，包括建立和销毁  

## 运行截图  
![](https://github.com/chinaporn/91PornCrawler/raw/master1/crawler.png)

## 线上演示
<details>
  <summary>访问目标包含成人内容,请谨慎查看!</summary>
  <p>
    
  #### 注意：默认已屏蔽CN,所以大陆无法访问!

  ```python
  >>> base64.b64decode("Hidden")
  ```
  </p>
</details>

## 开发记录

#### 已完成

- [x] 页面CSS框架升级至[ Bootstrap 5 Beta](https://getbootstrap.com/docs/5.0/components/collapse/) 测试版
- [x] 页面布局对手机版进行重新适配
- [x] 增加初版的排序功能
- [x] 微调,包括边距的优化,不同设备的内容可见性

#### 计划中
- [ ] 重新开发搜索功能 改用全文搜索系统

#### 脑洞中
- [ ] 基于AI的视频修复功能,来提高视频的清晰度


