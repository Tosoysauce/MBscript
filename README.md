#说明
此仓库备份大佬的脚本,脚本使用请看使用说明,如无法加载教程图片请带上梯子访问.⭐

微信项目：
立即参与 -> http://h5.qingxue.xyz/j/r2?upuid=161437&ch=xmy
备用链接 -> http://h5.jiangqz.xyz/j/r2?upuid=161437&ch=xmy

需要抓包以下内容:
打开微信，进入阅读，在如下界面

./blob/main/QQ%E6%88%AA%E5%9B%BE20210628124952.png

打开抓包惊喜抓包，然后回微信界面，点 点击阅读，开始零钱

如果需要验证就点验证，会进入一个微信文件界面后直接 点 左上角 关闭即可 （不要点返回键，不要点返回键，不要点返回键）

完成后进入抓包软件

抓包是搜索：pageshow 或 do_read 

或者url中：pageshow 或 do_read 

然后找如下图中的东西

https://github.com/Tosoysauce/MBscript/blob/main/QQ%E6%88%AA%E5%9B%BE20210628122128.png

单独长按就可以复制 Value 

然后shuye配置（青龙/v2p自行测试）添加变量

export Readck="复制的cookie"  ## 包含 PHPSESSID=xxx;udtauth==xxx

export ReadckAgent="协议头"  ## User-Agent 的值，不包含 User-Agent

https://github.com/Tosoysauce/MBscript/blob/main/QQ%E6%88%AA%E5%9B%BE20210628122906.png

添加完就如此

注：
1.本人测试为shuye面板

2.可能每执行都得去微信验证一次

3.shuye面板我搞定时好像不行，得手动执行，有大佬可以提供一些啊

4.青龙拉取：添加定时任务 在命令那里粘贴 ql raw https://github.com/Tosoysauce/MBscript/blob/main/10sRead.js

5.shuye面板的我不会拉取命令，只能自行上传到服务器。shuye拉取有大佬会的可以提供一些啊，脚本地址
https://github.com/Tosoysauce/MBscript/blob/main/10sRead.js

原仓地址：https://cdn.jsdelivr.net/gh/Wenmoux/scripts@wen/other/jrkuaixun.js

