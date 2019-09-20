# html5-speedtest
一个基于HTML5的Speedtest 开源速度测试(服务器网速)精简汉化

原版地址:https://github.com/adolfintel/speedtest

## 演示地址

[speedtest.isoyu.com](http://speedtest.isoyu.com)

## 兼容性

支持所有现代浏览器：IE11，最新Edge，最新Chrome，最新Firefox，最新Safari。
也适用于移动版本。

## 服务器要求
* Apache 2速度相当快的Web服务器（nginx，IIS也支持）
* PHP 5.4（其他后端也可用）
## 更新时间

2019年6月23日 03:05:17
url_getIp:"getIP.php"更新为url_getIp:"ip.php"，使用更友好带运营商显示的纯真ip数据库，地理位置没ipip精准，但是带运营商！ping汉化改成延迟。

2019年3月3日 02:04:35
代码使用官方最新版，汉化修改一处错误翻译，更新ipip数据库最新版，提高代码运行稳定性。

2018年4月7日 07:13:14
更新ipip最新datx数据库，查询更快，响应延迟缩短到1ms，ping通过调用谷歌浏览器api直接实现，次数修改为20次，测速时间修改20秒，启用多线程测速下载和上传，需要使用h2环境下运行，否则不起用多线程，修改一处汉化字符错误。


使用方法，放入服务器空间中，进行访问，需要环境支持php，推荐使用http2模式。

## 捐
[捐赠](https://github.com/insoxin/donate/blob/master/README.md)  
