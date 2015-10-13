# 优化电脑 Ccleaner

Windows **标准的文件删除方法**（```Delete```）并不能将实际数据从硬盘上消除（即使清空回收站——及时清空回收站也是有必要的）。临时文件也一样。时间久了，没用的信息会积累很多，占用内存。CCleaner 可以通过擦除空闲硬盘空间来安全删除旧信息。

[CCleaner](https://www.piriform.com/) 是一款易用、高效、免费的程序，通过永久性删除（或称「擦除」）浏览器历史记录、cookies、其他所生成的临时文件、释放硬盘上的空间。

---

### 1. 设置
（1）【选项】---【设置】---【安全删除】

（2）选择**文件安全删除（较慢）**，下拉菜单中一般选择**简单覆写（1遍）**或者**高级覆写（3遍）**就行。
<div style="text-align:center">
<img src="https://40.media.tumblr.com/22b985f369b57096e58ea000b034c5b5/tumblr_nw58bx5gjG1uft3xho1_1280.png"/>
</div>

## 

### 2. 删除临时文件
「清洁器」窗口被分为两格，左边显示 Windows 和应用程序选项卡，而右边的空白区域则显示每次清理操作的信息和结果。分析和运行清理器按钮是位于空白区域下方。

（1）**【清洁器】左侧框的 Windows 和应用程序中选择需要清理的内容**，右侧空白区显示分析、清理过程。

 * Internet Explorer 项可以都选择
 
 * 向下滚动 Windows 和应用程序选项卡，把**高级**部分的选项也全部选上，选上某些选项时，会出现警告、确认对话框。
<div style="text-align:center">
<img src="https://41.media.tumblr.com/8603e72a061c785369efb16077fecb02/tumblr_nw58bx5gjG1uft3xho2_1280.png"/>
 <img src="https://41.media.tumblr.com/6f05f1b4d206111b87adf5af28277f77/tumblr_nw58bx5gjG1uft3xho5_540.png"/>
 </div>

（2）**选择完毕，进行分析**

 **注：分析中可能会出现如下图提醒。可以先跳过清理，也可以关闭。**
 <div style="text-align:center">
 <img src="https://40.media.tumblr.com/3d099efe0cff6e97d6a01282aa4d2bc7/tumblr_nw58bx5gjG1uft3xho4_500.png"/>
 </div>

（3）**分析完毕，【运行清洁器】，弹出确认对话框**

*CCleaner只会删除所使用的应用程序所生成的临时文件，而不会删除应用程序本身。*

## 

### 3. 定期清理 Windows 注册表

一个储存了配置信息和您系统里的硬件与软件设定的数据库。每次改动系统配置信息、安装软件或进行其他日常工作时，这些改变都会在 Windows 注册表中反映并保存。

然而，久而久之，Windows注册表会积累过时的配置信息和设定，包括废弃的程序的痕迹。CCleaner 【注册表】选项帮助扫描并移除这些信息，提高系统的整体性能和速度，也保护到用户信息隐私与安全。

**提示：**Windows 注册表的扫描应该每月进行一次。

（1）切换到**注册表**界面

（2）勾选注册表完整性列表里的所有项目，然后点击【扫描问题】
<div style="text-align:center">
<img src="https://41.media.tumblr.com/74d2d60b0804ee84f73e5832057c9066/tumblr_nw58bx5gjG1uft3xho6_r1_1280.png"/>
<img src="https://41.media.tumblr.com/3991a7acafe0f02379f0c67f49dde840/tumblr_nw58bx5gjG1uft3xho7_500.png"/>
</div>

（3）点击【修复所有问题】，弹出备份对话框

<div style="text-align:center">
<img src="https://40.media.tumblr.com/2e0a6093c5a87b0739f8328700b23d6d/tumblr_nw58bx5gjG1uft3xho8_400.png"/>
</div>

开始修复 Windows 注册表的问题之前，你会被要求保存一个注册表的备份文件，有备无患。如果在 Windows 注册表被清理之后出现了问题，可以使用备份文件把 Windows 注册表还原至原本的状态。

**如果忘记把注册表备份文件储存在哪里，可以直接搜寻 *.reg* 文件扩展名。**

（4）备份完毕，点击【修复所有选定问题】

高级或专家级别的用户喜欢根据自己的需求，修复其中一些问题而忽略其他。对于一般用户和入门用户，推荐**直接修复所有问题**。

<div style="text-align:center">
<img src="https://41.media.tumblr.com/c56cc3b930332fb888427d925e7dc113/tumblr_nw58bx5gjG1uft3xho9_500.png"/>
</div>

（5）恢复原来的注册表（备用）

* 1）Windows 键+ R ,然后输入** regedit**

* 2）在新的对话框内，从菜单栏选择 **文件 **> **导入**以激活导入注册表文件的画面，然后选择自己备份的注册表文件。**确定**

 <div style="text-align:center">
<img src="https://41.media.tumblr.com/48bd62b85f5bf79c3b6b5d03448d9913/tumblr_nw58bx5gjG1uft3xho10_1280.png"/>
</div>

## 

### 4. 卸载电脑上的软件

Ccleaner 还可以帮助卸载、删除安装的程序。

（1）**工具—卸载**

（2）**运行卸载程序**后，有时还需要**删除条目。**

<div style="text-align:center">
<img src="https://40.media.tumblr.com/c42e706aa033bc551d0871514f56b13f/tumblr_nw58chEjYD1uft3xho2_1280.png"/>
</div>

## 

**提醒**：一般，Ccleaner 在关闭其他程序（浏览器、播放器、文档编辑器等）之后，可以手动扫描分析，清除无用内容。

在电脑正常使用中 Ccleaner 也会自动扫描清除。
<div style="text-align:center">
<img src="https://41.media.tumblr.com/8eb54ace5e2af31f3f98b0b48f1a82f4/tumblr_nw58chEjYD1uft3xho1_r2_400.png"/>
</div>

---

**参考资料**：[
CCleaner - 安全文件删除与工作进程擦除](https://info.securityinabox.org/zh/ccleaner)

*Ccleaner 使用完毕，持续更新......*