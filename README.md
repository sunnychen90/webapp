# 在线阅读器-webapp
#
# 创建时间：2016-11-16 22:08:50
#
# 创建人：Sunnychen90

#项目总体思路：
#   
#   前期，先在本地存储一些本地资源，能够将数据顺利展示
#   
#   中期，能够使用接口获取资源
#   
#   后期，通过爬虫(python)，去一些资源网站爬取文章资源，将资源入库，提供api接口

#   相关功能：
#
#          阅读文章，
#          支持夜间模式
#          可以改变阅读器字体大小
#          可以修改皮肤
#
#
#
#  这个项目主要是采用html5 进行编写
#  里面是用到的库有：
#               1. zepto.min.js (http://zeptojs.com/zepto.min.js)
#    			2.jquert的插件：jquery.base64.js (此文件用来对图片进行base64位处理)
#               3.jquery.jsonp.js 此文件是对从接口获得数据，防止跨域时，获取不到数据，所以采用jsonp		
#
#
#  文件夹：
#       css:放入css样式文件，其中包括reset.css(重置样式表),以及index.css(项目css),和一个base64图片的txt
#
#       js: 这里放入的是jquery.base64.js以及jquery.jsonp.js
#
#       lib: 这里放入的是zepto.min.js
#
#       data: 这里放入的是本地写的json文件，在前期就是使用的这些本地数据
#
#       入口页面： index.html
#
