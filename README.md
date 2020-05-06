# 大学之巅：2600多所高校数据        
2018年8月，对先网数据做了一些整合和清洗，基于此开发了一款小程序和简单写了一个网站。都转型产品经理了，这些数据还是要分享给程序员小伙伴们的。希望可以给做相关应用练手的同学或者独立开发者提供原始数据。下面是各文件夹数据解释：       

- 大学详情：2600多少高校信息，包含地址、人数、博士点、简介、logo、图片等；
- 各行政区大学列表：可以做分类；
- 大学目录：1个json文件，可以做搜索使用；
- 全国普通高等学校名单.xls：最原始的大学列表，作为参照索引；


# 效果    
#### 1.小程序: 大学之巅
![](https://dxzd-js-css.oss-cn-hangzhou.aliyuncs.com/001.jpeg)        
![](https://dxzd-js-css.oss-cn-hangzhou.aliyuncs.com/002.jpeg)      
也可以扫码体验：       
![](https://dxzd-js-css.oss-cn-hangzhou.aliyuncs.com/dxzd_minapp.jpg)       


#### 2.Web 网站: 大学之巅     
网址： https://aissues.com/    


#### 3.Web 网站: 大学地图    
网址： https://aissues.com/university-map/



# Q&A  
Q：原始数据要不要处理          
A：需要的，最好写个 node.js 程序将图片和数据上传到云存储；

Q：小程序技术方案选择什么好？      
A：选择[小程序云开发](https://cloudbase.net/?from=vczero)，既可以做为数据存储和后端服务，还可以天然和小程序结合。


[项目地址](https://github.com/vczero/serverless-colleage)：https://github.com/vczero/serverless-colleage       

