tieba-sign-install2【已失效】
===================

[2014年8月30日]由于KK的签到项目停止维护并关闭API，tieba-sign-install2贴吧签到助手安装项目关闭。

用于在Openshift创建应用时直接引用自动安装签到助手。

详细安装教程请戳[创世神域](http://www.puteulanus.com/?p=442)。

###新版特性：

**1.强大的文件管理器。**

上一个版本的文件管理器就是想让搭建的朋友能不用撸钥匙、winscp，可惜效果不佳。这回换了个文件管理器，我能想到的功能它都有了，还带了一票用不着的功能。。。反正有这货应该是可以把winscp丢一边了。

**2.自定义的用户信息**

上个版本中，我自动生成了所有的用户信息，虽然看起来一步到位，其实也不怎么方便。这次更新的版本重新修改安装界面，只留下了用户名、密码、用户邮箱三个项。简介的同时不影响使用体验。

**3.在线数据库管理**

好吧这个是作为文件管理器插件存在的【所以说那个文件管理器功能多的吐不出槽啊】，我稍微改了改，弄成了自动获取数据库信息，这样直接连接就能在线管理数据库。

**4.更稳定【貌似吧】**

我做了一些细节的调整，争取让它运行的更稳定。有没效果就难说了。。
###FAQ  

Q:遇上计划任务故障的提示怎么办？  
A：不管。

Q:自动备份目录在哪儿？  
A:自动备份会每天备份数据库到.openshift/backup/sql目录，保存三天的

Q:配置文件搞丢了怎么办？  
A:在.openshift/下有备份的配置文件
