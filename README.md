# WechatSpider
基于python+appium的android微信自动添加好友及爬取其朋友圈的爬虫
使用方法：
1.安装android SDK，并在环境变量中添加ANDROID_HOME变量，变量地址为SDK的地址
2.安装appium
3.android手机通过usb接口连接电脑，打开usb调试，选择连接方式为传输文件
4.打开appium并启动服务器
5.运行程序
注意：
不同版本微信可能控件id不同，可以通过android sdk里的uiautomatorviewer或者appium设置session获取自己手机微信的控件id，并替换文件中的id。
