# 文件同步与共享

### 1. BitTorrent Sync 是什么

BT sync 是一个文件同步/分享工具，可以在不同设备、网络间同步与分享文件。
同步/分享文件功能有这些特点：

* 数据安全。电信运营商是无法知道文件内容的。

* 文件数量**无限制**，文件大小**无限制。**现在普遍使用的各种网络云盘（Dropbox、Box、Google Drive、One Drive、百度网盘、腾讯微云等）都对上传/下载文件数量、大小有限制。

* 没有存储空间限制。存储空间大小取决于电脑上存储这些文件的硬盘大小。

* 使用完全免费。不再为是否购买商业网盘纠结。

* 便捷。如果出门办公前不想背（提）着重电脑到处跑，但又希望使用到自己电脑里的一些文件，可以用 BT sync 同步到办公地某台设备上使用。

* 与一般云端硬盘不同，它可以寻找设备间最短的传输路径，比云端硬盘更快（16倍速）。只会同步出现更新的文件。

* 分享、同步时，电脑必须开着。

* [2.2 以后版本，免费用户可同步/分享10个以上文件夹](http://blog.getsync.com/2015/09/09/sync-2-2-now-available/)


编者以前在对比挑选诸多网盘时总觉得每一个都不满意，Dropbox、Box、Google Drive 一类虽然相对安全些，但提供的免费空间有限，而且网站访问不方便，上传、下载慢。国内的百度网盘、腾讯微云一类提供的免费空间比较大（500G 以上），但下载不方便，而且最重要一点是并非任何文件都可以放心地存储在上面（即使手动给文件上锁），不知哪天某些文件就莫名其妙地消失，无法使用。

--- 

### 2. [下载](https://www.getsync.com/)、安装
（1）下载安装后会自动在浏览器中访问  http://127.0.0.1:8888/ ，进入 BT Sync 管理界面。

<div style="text-align:center">
<img src="https://41.media.tumblr.com/c04829592722930243c4095d34d91693/tumblr_nw46m7OmUE1uft3xho1_1280.png"/>
</div>

*注：如果系统的 IE 版本比较低，BT Sync 会自动弹出系统中的默认浏览器。*

<div style="text-align:center">
<img src="https://40.media.tumblr.com/2800d0097c149abaa87c6888766d34a5/tumblr_nw46m7OmUE1uft3xho2_r1_400.png"/>
</div>

（2）**创建用户名和密码，用于以后登录管理界面。**

（3）创建一个用户名，以后接收、分享文件时公开显示的名字。下图红圈处勾选。

<div style="text-align:center">
<img src="https://41.media.tumblr.com/470fd85b989d7c528c5748f458a3ba98/tumblr_nw46m7OmUE1uft3xho3_r2_540.png"/>
</div>

（4）从右上角锯齿进入【我的设备】，**更改设备名称**。

BT Sync 默认会使用当前系统的主机名，作为它的节点名（也叫「设备名」）。

如果你对隐私比较在意，建议把 BT Sync 的设备名修改掉，改成一个跟你本人真实身份无关的名称。

<div style="text-align:center">
<img src="https://41.media.tumblr.com/017f81304be98e731b0e1726567186e8/tumblr_nw46wf4NFy1uft3xho1_1280.png"/>
</div>

--- 

### 3.  接收文件

（1）从右上角锯齿进入【手动链接】

<div style="text-align:center">
<img src="https://41.media.tumblr.com/51831708a5a9b089f2d92610c3689056/tumblr_nw46m7OmUE1uft3xho5_r1_400.png"/>
</div>

（2）输入其他设备生成的密钥或链接（多为密钥），下一步

<div style="text-align:center">
<img src="https://41.media.tumblr.com/f5a17fc8127bc125cdca0e205f2dda02/tumblr_nw46m7OmUE1uft3xho6_r1_1280.png"/>
</div>

*比如我生成的一个文件夹分享密钥：B5RF536JNBL2OGJL5ZY5EFWDJCFEX62RY*

（3）选择/创建一个文件夹用于接收同步资料

<div style="text-align:center">
<img src="https://40.media.tumblr.com/188271facf6331219dcd96d81df1f31a/tumblr_nw46m7OmUE1uft3xho7_r1_1280.png"/>
</div>

**注：在选择的同步目录里面会创建一个名为 .sync 的子目录。这个 .sync 目录会包含 BT Sync 的一些配置信息（可能该目录的密钥也在里面），你可别把它给删喽。**

**（4）修改同步目录的选项参数**


* 下图**红1**依据个人喜好设置。

* **红2建议都勾选。**

* **如果同步内容不在局域网上，不要勾选红3。**

<div style="text-align:center">
<img src="https://41.media.tumblr.com/e78b8ff78f69f97dbc1384c3895227db/tumblr_nw46m7OmUE1uft3xho8_r1_1280.png"/>
</div>

---

### 4. 同步/分享自己的文件

（1）点击添加文件按钮。管理界面如下图圈出的按钮

<div style="text-align:center">
<img src="https://40.media.tumblr.com/8a8cd9421cfccf31d29a2460703ef1c3/tumblr_nw46m7OmUE1uft3xho9_r1_400.png"/>
</div>

（2）选择【标准文件夹】，【继续】

<div style="text-align:center">
<img src="https://41.media.tumblr.com/de7bcd515b6e87f711d67eceac095106/tumblr_nw46m7OmUE1uft3xho10_r1_540.png"/>
</div>

（3）选择需要同步/分享的文件夹。**一次只能选择一个文件夹，无法直接选择具体文件。**

<div style="text-align:center">
<img src="https://40.media.tumblr.com/188271facf6331219dcd96d81df1f31a/tumblr_nw46m7OmUE1uft3xho7_r1_1280.png"/>
</div>

（4）【打开】待同步文件夹后，会自动弹出同步/分享设置窗口


* 权限默认【只读】即可，除非允许同步该文件的人（也可以是自己）编辑它。
* 安全性，如果想长期同步/分享该文件夹，可取消第二勾。
* 如需要将分享链接通过电邮告知别人，可点击**3**操作。

<div style="text-align:center">
<img src="https://41.media.tumblr.com/0f472e981360dd016c85f18daf0a82bd/tumblr_nw46wf4NFy1uft3xho2_1280.png"/>
</div>

* 1）上图【密钥】中一个是【只读】密钥，一个是【读写】密钥。

**注：如果只允许别人同步查看你的分享文件，只需公开【只读密钥】！！！**
辨识只读密钥、读写密钥：只读的以 B 开头，读写的以 A 开头。

<div style="text-align:center">
<img src="https://41.media.tumblr.com/9602b6a469e099147f9d127f1f47ac63/tumblr_nw46wf4NFy1uft3xho3_540.png"/>
</div>

2）如需手机等编写设备扫二维码获得同步/接收，提供 **QR 代码**即可。（一般很少用）

--- 

参考资料：http://program-think.blogspot.com/2015/01/BitTorrent-Sync.html#comment-form

*此篇总结完毕，持续更新......*
