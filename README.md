# -Android-下载地址：http://ym.maptoface.com/2021/05/16/%e3%80%8aandroid%e7%b3%bb%e7%bb%9f%e5%bc%80%e5%8f%91%e3%80%8b%e8%af%be%e7%a8%8b%e8%ae%be%e8%ae%a1%e8%af%be%e7%a8%8b%e6%8a%a5%e5%91%8a/

项目介绍
《Android系统开发》课程设计

系统说明
 

 

 

 

 

 

天气预报APP

 

 

 

 

学号：

 

姓名：

 

指导教师：

 

 

 

 

 

 

目录

程序框架结构
首页展示默认城市的天气情况,包括当天的详细信息和后4天的大致信息,可以从右上角按钮跳转到收藏城市列表,收藏列表从SQLite数据库查询出所有收藏城市的数据,点击可以跳转回首页 并显示该城市的天气,可以多选城市之后删除,点击添加按钮可以搜索并添加城市,并将城市信息存放入数据库中

 

 

 

 

 

                    

 
 	 
 

 

 

 

 

 

 

UI界面
背景及天气图标等:

 

 

 

 

 

 

 

 

 

 

Intent 和Activity的使用
 

一共使用了3个activity,分别是:MainActivity首页,CityActivity收藏城市页面,SearchActivity搜索城市页面

通过intent实现从首页跳转到收藏城市列表页面,并通过bundle传递信息

通过intent实现点击添加按钮,从收藏城市页面跳转到添加城市页面

使用API借口调用天气及城市更新
在首页通过调用极速数据API发送http get请求,请求天气数据,并解析返回的json数据 在首页中展示:

通过服务刷新天气及城市:

获取省市县:

 

BaseAdapter的使用
自定义Adapter实现列表多选

SQLite数据库的使用
使用SQLite数据库存储数据信息

适用场景：
毕业论文、课程设计、公司项目参考

运行截图
点击并拖拽以移动​ 点击并拖拽以移动​ 点击并拖拽以移动​ 点击并拖拽以移动​ 点击并拖拽以移动​

关注【程序代做 源码分享】公众号获取更多免费源码！！！
点击并拖拽以移动​
