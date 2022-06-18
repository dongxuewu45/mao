# cat
https://ht09564.github.io/mao.json


猫影视接口TV本地化教程
本地接口 clan://协议流程说明：
“maotv”为本地接口文件。
“maolive”为本地直播源接口文件。
“custom_spider_0330.jar”文件为jar文件。
下载说明：
下载“maotv”，“maolive”，“custom_spider_0330.jar”，三个文件，并记住保存位置。
在本地文件夹中，将“maotv”、“maolive”、“custom_spider_0330.jar”，三个文件复制到新建文件夹内。
将直播源添加到“maotv”方法：
clan://新建文件夹名/maolive.txt。
将“1”的本地接口转换为Base64
打开maotv.txt文件，找到{"name": "redirect", "urls": ["proxy://do=live&type=txt&ext="] 位置。
将转换好的链接粘贴到["proxy://do=live&type=txt&ext="] 后面。
“custom_spider_0330.jar”文件配置：
打开maotv.txt文件，找到“蜘蛛”：“http:s//xxxxxxx.js;md5;01a4ac9109a0602124cee4feddc1971e”。
将js文件改成配置clan://文件夹名称/custom_spider_0330.jar。
将配置好的文件，替换掉，例如："spider":"clan://文件夹名/custom_spider_0330.jar;01a4ac9109a0602124cee4feddc1971e"。
猫影视本地接口配置：
配置路径为clan://localhost/文件夹名/maotv.txt。
