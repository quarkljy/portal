# 门户网站前端

##### 1. 前言

这是对外开放的门户网站的前端部分

##### 2. 修改配置

先修改大部分图片和跳转网页的href和src的绝对地址

使用idea的全局替换

![image-20200111142844602](https://leyou-oss-quark.oss-cn-shenzhen.aliyuncs.com/image-20200111142844602.png)

修改后台服务的api地址，在common.js 

![image-20200111143509000](https://leyou-oss-quark.oss-cn-shenzhen.aliyuncs.com/image-20200111143509000.png)

将文件夹下的上传到服务器的

/quark/nginx/html/portal-web文件夹下

我的nginx是docker安装的，/quark/nginx/html映射 的是 docker容器里/etc/nginx/html文件夹，所以必须这么放。