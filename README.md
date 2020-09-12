# WebGIS-Demo 开发与实战

+ 根据知乎 [《WebGIS入门与进阶实战》](https://xiaozhuanlan.com/topic/3614597820) 整理的学习笔记和成果。
+ 技术base: Html/CSS/JavaScript

## WebGIS概述
WebGIS（网络地理信息系统）是指工作在Web网上的GIS,是传统的GIS在网络上的延伸和发展，具有传统GIS的特点，可以实现空间数据的检索、查询、制图输出、编辑等GIS基本功能，同时也是Internet 上地理信息发布、共享和交流协作的基础。简单来说，Web + GIS 就是，在Web网页上的GIS系统，我们可以在网页（浏览器）上进行GIS数据处理操作、可视化展示等。

## 开发常用的地图JS库
+ OpenLayers：https://openlayers.org/
+ Leaflet.js：https://github.com/Leaflet/Leaflet
+ ArcGIS API for JavaScript：https://developers.arcgis.com/javascript/

## 目前库里有什么：
+ OpenLayers和ArcGIS API的地图服务加载展示demo（只有界面）
+ 基于Leaflet的台风实时路径实现
+ 基于Leaflet的个人旅游地图相册实现 （不能直接打开index，需要使用http-server工具部署）

## http-server 快速部署访问前端静态页面
通过CMD来进入到想部署访问的页面文件夹下，输入命令 http-server 即可部署成功，默认端口为8080。也可以使用 http-server -p 端口 来指定不同端口，部署多个demo，成功后，访问提示的地址即可 http://127.0.0.1:8081
