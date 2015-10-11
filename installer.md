# 正确安装软件

### 1. 应该从哪里下载

**官网/负责维护该软件项目的网站**

即使是第三方网站，也得是有人维护且可靠的。（如 [Github](https://github.com) 和 [Sourceforge](https://sourceforge.net/)  ）

任何一个软件都有其官方或专门维护的项目网站，从那里下载安装的软件包本身才可能相对安全。反之，从第三方网站得到的软件并不能保证这一点，两者比较直观的不同是，后者软件会附带广告（各种插件，如从百度下载；流氓软件，如360），隐形的不同可能出现植入恶意代码，泄漏用户信息。

不知道官方网站地址怎么办？Google 搜索软件名称，切勿使用**百度**，百度搜索总会将自家的[百度软件中心](http://rj.baidu.com)放在第一位，其他链接大多是乱七八糟的第三方地址，如果幸运一些，或许可以找到软件的官网。

百度 **Chrome**, 肯定会让你失望。
<div style="text-align:center">
<img src="https://41.media.tumblr.com/3588dc9b9e504ed8a89d528e27bde93f/tumblr_nvzwupow3v1uft3xho2_1280.png"/>
</div>

搜狗的结果还可以，检索第一页末尾还能见到 Chrome 官网链接。
<div style="text-align:center">
<img src="https://41.media.tumblr.com/d601321cfc207e99fd96cdfa88400bc6/tumblr_nvzwupow3v1uft3xho3_r1_1280.png"/>
</div>

*（关于搜索引擎的使用，有专门章节详细说明，此处略过）*

--- 
### 2. 安全校验

* **必要性：**无论从哪里下载的软件，都有必要查看安装包是否被篡改、被植入病毒。尤其通过非官方链接得到。

* 需要校验的内容：**「数字签名」是否有效，「数字证书」是否有问题**

「数字签名」是采用某种技术手段来证明某个信息确实是由某个机构（或某个人）发布的。因为其用途有点类似于传统的手写签字，所以称之为「数字签名」。

大多数软件安装文件都附带有数字签名。

「数字证书」是「数字签名」的组成部分。

#### 2.1 在资源管理器中校验数字签名、数字证书（以 Firefox 为例）

 1. **右键待校验安装文件**（.exe 格式）进入【属性】，正常情况下，上方会有【数字签名】。
<div style="text-align:center">
<img src="https://40.media.tumblr.com/e1ccde594093a33b72bc683f3693ffef/tumblr_nvzwupow3v1uft3xho4_r1_500.png"/>
</div>

 2. 点击【数字签名】，进一步【详细信息】到下图。
<div style="text-align:center">
<img src="https://40.media.tumblr.com/af1206bfc7f233fb9fadac180f342d26/tumblr_nvzwupow3v1uft3xho5_r1_500.png"/>
</div>

 3. 新界面会显示一行字：**此数字签名正常**。如果有这行字，就说明该文件从出厂到你手里，中途没有被篡改过。
反之，出现一个警告提示：**此数字签名无效**，那么这个文件就不要再使用了。

 4. 在** 2. **的界面点【查看证书】按钮，弹出证书的对话框。在【证书路径】里可以看到每层证书状态。
<div style="text-align:center">
<img src="https://41.media.tumblr.com/e1b094f4cbfbafc26359c2f7dae17ff0/tumblr_nvzwupow3v1uft3xho6_r1_500.png"/>
<img src="https://41.media.tumblr.com/69f3d18dc281819683039d420a4d97f2/tumblr_nvzwupow3v1uft3xho7_r2_500.png"/>
</div>

校验完毕，如无异常，可以开始安装。

**注意：一旦数字签名无效或者数字证书有问题，不要安装该软件。**

**参考资料：**http://program-think.blogspot.com/2013/02/file-integrity-check.html#head-7



--- 
### 3. 正确安装

**原则：**选择**自定义选项**安装，**不采用标准模式（快速安装模式）。**
<div style="text-align:center">
<img src="https://41.media.tumblr.com/3690f302b8fc4d13e203bc3e4094b3f5/tumblr_nvzxxieFA11uft3xho4_r1_1280.png"/>
</div>

#### 3.1 安装位置的选择

## 

* 非 C 盘（系统文件盘）
* 一般选择其他盘的 Program Files (x86) 或 Program Files 文件夹
* 手动**新建文件夹**，并以该软件的名称命名——方便以后管理

## 

#### 3.2 更改默认设置

* 关闭「开机自动启动｣，可提高开机启动速度。如上图 QQ 安装默认开机自动启动，需手动取消；

* 是否添加图标于【开始】菜单；

* 是否固定图标于桌面状态栏——左键一下就启动；

* 取消附带的无关程序安装；

* 关闭「用户使用信息反馈回XXX」；

* 设置【开机启动项】，取消/添加已安装软件开机自启动；

* 关闭「设置XX为浏览器首页」（如下图搜狗拼音、QQ 安装，*要注意「设置搜狗导航为您的默认首页」*）

<div style="text-align:center">
<img src="https://41.media.tumblr.com/27c1ac9d721750174f288accf4a2e0e7/tumblr_nvzwupow3v1uft3xho9_r1_1280.png"/>
<img src="https://40.media.tumblr.com/ab3936d41b1eaff172cc6a03ef6796b0/tumblr_nvzwupow3v1uft3xho8_r1_1280.png"/>
</div>

## 

#### 3.3 开机启动程序设置

 1. ```Winkey+R``` ，输入 ```cmd```，【确定】
![image10](https://41.media.tumblr.com/db83d1110c8981983cd23a5a86e5392b/tumblr_nvzwupow3v1uft3xho10_r1_500.png)
 
 2. 在新的对话框内输入```msconfig```
<div style="text-align:center">
<img src="https://40.media.tumblr.com/48bf6f54b03a99a95e87a07f054f45e9/tumblr_nvzxxieFA11uft3xho1_1280.png"/>
</div>

 3. 弹出新的对话框【系统配置】，选择【有选择的启动】，点击【启动】
<div style="text-align:center">
<img src="https://41.media.tumblr.com/ef364ae99c85d9646dff32a0a649e211/tumblr_nvzxxieFA11uft3xho2_1280.png"/>
</div>

 4. 根据自己具体情况，取消自己安装的部分软件自启动。重启系统。
<div style="text-align:center">
<img src="https://41.media.tumblr.com/776ea4f7785b63836bc933443c6faddb/tumblr_nvzxxieFA11uft3xho3_400.png"/>
</div>

## 

#### 3.4 设置缓存存放位置

如上面安装 QQ 截图，可自定义消息数据存储位置，**一般更改为非 C 盘（系统盘）。**
有些软件（多为媒体播放器、图片处理工具、浏览器）在安装、启动后可设置。

--- 
### 4. 正确卸载

* **方法：**【控制面板】——【程序卸载】中，右键软件卸载。
如需卸载多个软件，等待前一个卸载完毕再进行下一个。

 <div style="text-align:center">
 <img src="https://41.media.tumblr.com/a17064ecefcbdf4b2af2eb587ae12a0b/tumblr_nvzxxieFA11uft3xho5_r1_1280.png"/>
 </div>

* **注意1：**卸载时注意删除配置信息

 <div style="text-align:center">
 <img src="https://41.media.tumblr.com/6a56e277e8a362c19b9a65e01623078c/tumblr_nvzxxieFA11uft3xho6_r1_1280.png"/>
 </div>

* **注意2：**软件安装文件卸载完毕，但一些用户设置信息、缓存仍有残存。找到安装文件夹，删除即可（一般文件名就是该软件名）

 <div style="text-align:center">
 <img src="https://40.media.tumblr.com/48bde5fe83cfa7f4a2d73e053a7a7156/tumblr_nvzxxieFA11uft3xho7_r1_400.png"/>
 </div>
 
 
*总结完毕，持续更新...... *