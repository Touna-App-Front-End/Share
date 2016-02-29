title: 投哪网前端分享讨论会01
speaker: SimMan
url: https://github.com/ksky521/nodePPT
transition: zoomin
files: /js/demo.js,/css/demo.css

[slide]

# 投哪网前端分享讨论会01
## 演讲者：李伟、吴明媛、李军

[slide]

# 大纲
----

- 一、为什么有这个分享会
- 二、目前存在的痛点
- 三、该如何解决

[slide]

# 一、为什么有这个分享会

- 1、激(基)情
- 2、**知识能力拓展**
- 3、Kpi

[slide]

# 二、目前存在的痛点

原生App开发现状：[http://touna-app-front-end.github.io/Share/Touna-App-Front-End-Study01/publish/Touna-App-Front-End-Study01.htm#16](http://touna-app-front-end.github.io/Share/Touna-App-Front-End-Study01/publish/Touna-App-Front-End-Study01.htm#16)


[slide]

# 三、该如何解决

# 业界方案


方案 | 语言 | 容器 |优点 | 缺点 |
------------ | ------------- | 
ionic | (cordova + angular + UI library) | webview | H5 | 性能低下、效果差 
ReactNative | JSX | Native | H5+Native | 相比Native低百分之15% 
WeX5 | js | Webview | H5 |  

. | .
----- | ------
H5:  | web技术无法解决一切问题，对于比较耗性能的地方无法利用native的思维实现优势互补
Native:| 拥有native的用户体验和web的开发效率. learn once, write anywhere

[slide]

# 目前的解决方案

方案 | 使用场景 | 问题 |
-----| -----
JSBridge | 活动页面、社区、分享 | 性能、可扩展性
Html5 | 介绍、详情页面、BBS | 性能、在网络不稳定的情况下,有样式、脚本没有加载完情况。

[slide]


# 前端App技术架构转型

**使用 ReactNative 架构**

* 1、团队分成两批人,一批人负责原有项目的开发、维护,另一批人负责新架构的实现(完全重写,人多任性!)
* 2、新架构的时间节点是6.15前出一个可用的预发布版本。

[slide]
# please help us developing occt

* 1、前端团队: UI的布局与JSX的指导！
* 2、测试团队: 针对新架构实现的验收！
* 3、后端团队: 应用增量更新与升级方案!

[slide]
# 开发计划

周期 | 截止 |    内容      | 人员 |
--- | ---- | ----- | -----
1   | 03.07| React入门学习| 李伟、彭剑锋
2   | 03.14| 对现有项目进行分模块(原生、逻辑、UI) | 李伟、彭剑锋
2   | 03.15
6   |      | 实际开发 | 李伟、彭剑锋、后端
1   | 03.15| 测试介入 | 测试

[slide]
## 参考链接

- [移动WebApp开发 JS框架对比](http://zhangdaiping.iteye.com/blog/1613929)
- [React Native 官方文档中文版](http://wiki.jikexueyuan.com/project/react-native/)
- [ionicframework](http://ionicframework.com/)
- [framework7](http://www.idangero.us/framework7)
- [amazeui](http://amazeui.org/)
- [React-Native指南](https://github.com/ele828/react-native-guide)
- [如何评价 React Native？](http://www.zhihu.com/question/27852694/answer/38850201)
- [React-微信支付-android](https://github.com/beefe/react-native-wechat-android)
- [React-微信支付-iOS](https://github.com/beefe/react-native-wechat-ios)

---

[slide]
# THANK YOU!