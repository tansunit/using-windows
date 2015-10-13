# （解）压缩

### 1. WinRAR

* WinRAR 是一款压缩解压软件，为什么需要它，编者比较片面的几个应用方面：

* 网络传输，无论对于早期还是当下现状，假设一个压缩包下载并解压花费的总时间要比未解压的直接下载时间还短，这不就是所谓的效率吗？

* 空间占用，如果有些暂时不用但占用空间较多的资源，先压缩放一边不占那么多，硬盘还是那么多，这样空闲容量变大。

* 存储方式，想想快递寄件前如果不先打包，而且每个客户寄的都是一堆堆的零散的小东西，不但输送过程不方便，收件者也会烦心吧？

* 之所以提及 WinRAR 是因为编者一直以来都使用它（其实是没有用过其他的，毕竟只是日常使用完全足够），网上部分系统安装时会自带其他解压软件，比如好压是编者见过最多次的，因为名字像烤鸭而且图标太亮了。

* WinRAR 能解压、压缩，并附带直接邮件功能（email 功能没有用过，因为不知道它会以何种方式帮我发送，或许你可以亲自尝试下），这就 OK了。


关于右键菜单，编者出于简略右键菜单的考虑，采取的处理是安装时选右键菜单折叠，也就是对于文件的右键菜单所有的WinRAR 选项变为一个条目下的子目录，这个选项对于右键菜单需要比较多其他软件功能的情况下比较有利，分级管理的思想能在这里能为搜索效率与功能集成间取得一定的平衡吧至少。

下面是 WinRAR 的安装及使用的简单介绍：

这里选用的是自解压的安装方式（先有鸡还是先有蛋的问题），如图1右击选取「打开」，即进入安装选项如图3（这里由于某种原因，默认安装路径不是C盘），按默认路径即可（当然也可以选择其他），安装完成后将弹出图4所示对话框，建议勾选「外壳整合设置」中的「层叠」和「整合」选项，「确认」在文件上测试右键即可弹出图2所示 WinRAR.当然这里选择的测试平台是 Win XP 系统，但在其他 windows 平台上的操作情况类似，恕不一一演示。

<div style="text-align:center">
<img src="https://40.media.tumblr.com/50827aa0f02714ff9fef4d0409bf5735/tumblr_nw5a00FnH91uft3xho1_r1_400.png"/>
<img src="https://41.media.tumblr.com/3d2e554f3b45a954be0cd715703ca161/tumblr_nw5a00FnH91uft3xho2_500.png"/>
<img src="https://41.media.tumblr.com/fe7ae4f799f6b7ddd6437adcb997bee0/tumblr_nw5a00FnH91uft3xho3_540.png"/>
<img src="https://40.media.tumblr.com/485a8cca3fa70e44b96ca5108fa996a6/tumblr_nw5a00FnH91uft3xho4_540.png"/>
</div>

--- 

### 2. [7-Zip](http://www.7-zip.org)（最新稳定版：9.20；最新版：15.08 beta）

7-Zip 是一个免费、开放源代码、便捷的压缩、解压缩软件。其安装程序小（1M 左右）、操作简单、速度快。

#### 2.1 文件关联

（1）安装完成后，右键 **7-Zip File Manager **，选择**以管理员身份运行**。若出现对话框提醒，**是**即可。

<div style="text-align:center">
<img src="https://41.media.tumblr.com/a2b2c406889b3e2436f887bf7529bf60/tumblr_nw5a8bpscd1uft3xho1_400.png"/>
</div>

（2）关联文件：点击**工具---选项，**进入设置界面。

<div style="text-align:center">
<img src="https://40.media.tumblr.com/52d8d0050234393c5b9f9aa288fdc9d1/tumblr_nw5a8bpscd1uft3xho2_500.png"/>
</div>

（3）在**系统**一栏勾选关联项。
可以**全选**或只选择常用的 **7z/iso/rar/tar/zip**

<div style="text-align:center">
<img src="https://40.media.tumblr.com/234a27d22ad294c5fba13f5879f4fe99/tumblr_nw5a8bpscd1uft3xho3_400.png"/>
</div>

（4）**文件右键菜单7-Zip 选项设置**

默认情况下，右键菜单7-Zip 选项有很多，但有些不会经常用到（比如我不会经常用压缩并邮寄一项），可以在**工具—选项—7-Zip** 取消。
<div style="text-align:center">
<img src="https://41.media.tumblr.com/61984f5588738bc392eb5a0311cd1707/tumblr_nw5a8bpscd1uft3xho8_400.png"/>
<img src="https://41.media.tumblr.com/0c23afbb96a0cf1d8196320e6f601307/tumblr_nw5a8bpscd1uft3xho10_400.png"/>
</div>

## 

#### 2.2 压缩

由于 Windows 内建有解压缩** .zip** 的软件，即使没有安装 Winrar/7Zip 软件也可以打开，.7z 却不行。所以，一般压缩文件是自己使用，压缩成 .7z/.zip ，如果要给别人使用，压缩成 .zip 比较好。


**2.2.1 直接压缩**

在压缩文件之前，通常会将需要打包压缩的文件（夹）放在同一个文件夹中，然后右键选择 7-Zip 里的「Add to xxx.7z」或者「Add to xxx.zip」。
<div style="text-align:center">
<img src="https://40.media.tumblr.com/ce3704a93e849dcb86875f4b98c3fd37/tumblr_nw5a8bpscd1uft3xho4_1280.png"/>
</div>

## 

**2.2.2同时压缩多个文件（夹）**

压缩除了2.2.1 方法，还可以直接选择部分多个文件夹/文件，右键从 7-Zip 压缩。
<div style="text-align:center">
<img src="https://40.media.tumblr.com/e0e20ff52e3b87a5c72313d9caf0b049/tumblr_nw5a8bpscd1uft3xho5_1280.png"/>
</div>

## 

**2.2.3 先设置再压缩**

有时需要更改压缩文件存放位置或者压缩方式，以及在有必要时加密压缩。这时可以右键从 7-Zip 选择 **Add to archive **先设置再压缩。
<div style="text-align:center">
<img src="https://40.media.tumblr.com/1d5cba57f99253024f03770c986c4365/tumblr_nw5a8bpscd1uft3xho6_1280.png"/>
<img src="https://40.media.tumblr.com/2c30ef9f3d2c5e34eff60cefc89c3ce3/tumblr_nw5a8bpscd1uft3xho7_1280.png"/>
</div>

**选项说明**：

* **压缩包（A）**：后面点击选择压缩包保存位置；

* **压缩格式**：下拉可以选择 7z/tar/wim/zip 格式，一般选择常用的 7z/zip 就行。

 **注**：如果选择 **7z** 格式，建议顺便勾选**选项--创建自释放程序**，这样操作叫作「**自解压缩**」， 7-Zip 除了将要压缩的资料打包压缩，还会将 7-Zip 的解压缩应用一起打包进去，收到该压缩包的人不再需要安装任何解压缩软件就能直接解压缩出资料。

* **压缩等级、压缩方法**：均默认值。

 **注：如果想要压缩包更小，压缩格式选择 7z，压缩等级下拉选择极限压缩，压缩方法选择 LZMA2。**

* **分卷大小，字节**：用于**分割压缩**，下拉选择或者手动输入。

 （**分割压缩**指在要压缩的资料很大时，压缩软件不会把所有资料压缩成一个压缩包，而是按照设置的压缩包大小分割为多个，直到所有资料被压缩处理完毕。）

 ** 分割压缩**常用在 E-mail 对附件文件大小有限制，或者资料需要放进多个移动设备（U 盘/光盘等）。
<div style="text-align:center">
<img src="https://41.media.tumblr.com/3b8c2c7ec00af6869337ac810138e9fd/tumblr_nw5a8bpscd1uft3xho9_400.png"/>
</div>

* **加密**

重要资料可以加密压缩存放/传输。在右侧加密选项输入加密密码。

加密文件名：勾选后，压缩包双击打开时无法浏览内部文件，相当于把文件名也加密了。

## 

#### 2.3 解压缩

**2.3.1 直接解压缩**

双击压缩包，再选择里面的文件（夹），从压缩包托拽出来。
<div style="text-align:center">
<img src="https://40.media.tumblr.com/217ed0f4d4635cf4833c6b2ac59f139d/tumblr_nw5og2Hi7n1uft3xho1_500.png"/>
</div>

## 

**2.3.2 间接解压缩**

右键压缩包。

**Extract files**：选择解压缩保存位置、文件名

**Extract Here**：直接将文件解压缩在当前位置，每个文件显现

**Add to ......**：还可以进一步压缩

**如果压缩包是加密的，解压缩需要正确输入密码才会成功解压缩。**
<div style="text-align:center">
<img src="https://40.media.tumblr.com/d499d1b8769134599a01ba87ba7cd953/tumblr_nw5og2Hi7n1uft3xho2_500.png"/>
<img src="https://40.media.tumblr.com/d70bbcb07caa5ce019922b83752e1d9c/tumblr_nw5og2Hi7n1uft3xho3_500.png"/>
</div>


## 

**2.3.3 分割压缩包解压缩**

使用分割压缩方式压缩出来的文件副名称为**.001**、**.002**......，要将这些压缩包解压缩时，**一定要从.001压缩包开始，不可以从中间的编码开始！**此外，**当时压缩得到的压缩包在解压缩时都要在一起，一个都不能少！**

**由于.001副文件名并没有与任何应用软件关联，所以没有办法双击打开，只有通过右键选择 7-Zip 解压缩。**
<div style="text-align:center">
<img src="https://40.media.tumblr.com/66d455fa60cd0e10dd5e7f6f2f153162/tumblr_nw5og2Hi7n1uft3xho4_400.png"/>
</div>

--- 

### 3. WinRAR 与 7-Zip 比较

压缩纯文字文件：7-Zip 比 WinRAR 好，压缩包小，大约是 WinRAR 的五分之一。
压缩应用软件、图片：7-Zip 比 WinRAR 好，压缩包大约是 WinRAR 的十分之一。

--- 

**参考资料：**

* **[7-Zip 操作教学](http://changyang319.pixnet.net/blog/post/27861881)**

* **[7-Zip 压缩与解压缩](http://blog.xuite.net/yh96301/blog/26572744)**

* **[7-Zip 免费的超高压7Z 压缩软件](http://it-easy.tw/7-zip/)**

* **[WinRAR 5.0 與 7-zip 9.20 壓縮效率與使用評估](http://shaurong.blogspot.com/2013/09/winrar-50-7-zip-920.html)**


*总结完毕，持续更新......*
