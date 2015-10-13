# 电子书管理 Calibre

<div style="text-align:center">
<img src="https://41.media.tumblr.com/be0f2fb5ac73f9c21d14b4a3e0b8597d/tumblr_nw4zz3m2Vl1uft3xho1_1280.png"/>
</div>

### 1. 介绍

[Calibre](http://calibre-ebook.com) 是一款免费、开源的电子书管理应用。主要有以下七点功能：

* 图书管理
* 电子书格式转换
* 同步到电子书阅读设备
* 从网页下载新闻并转换为电子格式
* 电子书全预览
* 服务器支持在线访问藏书
* 为电子书编辑者提供主要的电子书格式

* 书籍在calibre的书库中保存时，能不能不要用拼音文件名？

 不能，calibre的作者不会针对这个问题有任何的改变。因为calibre就是这么设计的，它希望你通过它的界面去操作它所管理的文件，并不希望你直接去碰它的书库目录，而且用拼音保存可以有最好的跨平台和跨文件系统的支持。


* 可以用calibre编辑/修改电子书吗？

 calibre是电子图书管理工具，所以并不适合用来编辑修改电子书。如果硬要做也只能通过格式转换过程中的正则表达式替换来完成，所以还是建议用别的软件来修改电子书。

 对于epub和HTMLZ格式的电子书，calibre提供了“调整书籍”的功能，实际上是把电子书文件解包，用户手工修改后再自动打包起来而已。

* calibre可以从豆瓣网下载图书元信息和封面吗？

 可以，但这个功能在英文界面下默认是禁用的，只在中文界面下默认启用。但不管有没有自动启用，都可以通过首选项->元数据下载设置页来启用或禁用它。

 豆瓣网不提供精确匹配书名和作者的搜索接口，所以有时会返回一些不太靠谱的结果，这个只能靠人工来选择有用的结果了。
 
--- 

### 2. 格式转换

（1）**添加电子书到书库**

打开 Calibre, 点击左上角【添加书籍】，将想要转换的电子书添加到书库（也可以直接将电子书拖放到书库里）

（2）**选择一种转换格式**

选择一本或多本电子书，点击箭头，下拉菜单有**逐个转换**和**批量转换**可选。如果选取了多个文件，使用**逐个转换**需要对每一个图书进行单独的设置，比如可以对不同的电子书设置不同的格式；而**批量转换**则是所有电子书共用一个设置。
<div style="text-align:center">
<img src="https://41.media.tumblr.com/85c0b11a8740bbfba80ebb07abd3de79/tumblr_nw4zz3m2Vl1uft3xho4_1280.png"/>
</div>

*Calibre 支持转换的格式有：**EPUB**、**MOBI**、**AZW3**、**DOCX**、FB2、**HTMLZ**、LIT、LRF、PDB、**PDF**、PMIZ、RB、RTF、SNB、TCR、**TXT**、TXTZ、ZIP*

（3）**设置电子书信息**

对该电子书的「输出格式」、「元数据（包括书名、封面、作者等基本信息的设置）」、「界面外观（包括字体大小、内嵌字体、行高等内容格式的设置）」、「智能处理」、「页面设置」、「结构检测」、「内容目录」、「查找与替换」、「XXX 输出」、「调试」项进行详细的设置。
* **元数据**：如果书名、作者、封面信息不对，可直接修改；输出格式选择自己需要的格式（常用的为 MOBI/EPUB/PDF）
<div style="text-align:center">
<img src="https://41.media.tumblr.com/308a16c23df877ab483884a8b74940d0/tumblr_nw4zz3m2Vl1uft3xho8_1280.png"/>
</div>


* 界面外观：默认值即可（还没细细研究改动变量后的效果）
<div style="text-align:center">
<img src="https://40.media.tumblr.com/18922b5934147eab15ad1c269349cb4f/tumblr_nw4zz3m2Vl1uft3xho9_1280.png"/>
</div>


* **页面设置：输出配置一栏选择阅读设备**（比如这本 MOBI 准备在 kindle 上阅读，图例中选择 kindle ,这样会执行相关设定）
<div style="text-align:center">
<img src="https://41.media.tumblr.com/a3aa9a2f9cbaf476817ad9e83d942a4f/tumblr_nw525hiyZQ1uft3xho1_1280.png"/>
</div>


* **首选项-**-**保存图书到磁盘**，去掉3个勾选项：分别保存封面、在独立的 OPF 文件中保存元数据、将非英语字符转换为对应英语字符。

 **（如此设置保存图书时不会生成乱七八糟的文件，并可输出原文件名。）**
<div style="text-align:center">
<img src="https://40.media.tumblr.com/476a3e9cb0a2ba88181a0f901ed00c1c/tumblr_nw4zz3m2Vl1uft3xho3_r1_540.png"/>
</div>

（4）**查看转换进度：设置完开始转换格式，**右下角点击**任务**查看
<div style="text-align">
<img src="https://40.media.tumblr.com/dffb4bacef43c49463e05bf147843310/tumblr_nw4zz3m2Vl1uft3xho10_500.png"/>
</div>


 （5）浏览格式转换结束的书
<div style="text-align:center">
<img src="https://40.media.tumblr.com/f0a0862e65ce47f5f99ee09c022096e8/tumblr_nw525hiyZQ1uft3xho4_r1_1280.png"/>
<img src="https://40.media.tumblr.com/2465181bb61226e581a13f56f882835e/tumblr_nw525hiyZQ1uft3xho8_r1_1280.png"/>
</div>


（6）将转换好的 mobi 格式电子书推送到 kindle 设备
<div style="text-align:center">
<img src="https://40.media.tumblr.com/8d8e10ce967854a2cf167def6ff64330/tumblr_nw525hiyZQ1uft3xho2_r1_1280.png"/>
</div>

（7）删除已存在的书（指定格式）：如果不想把已推送到其他设备的书保存在电脑上可删除。
<div style="text-align:center">
<img src="https://40.media.tumblr.com/748d71338b38605a598f72414c6610c7/tumblr_nw525hiyZQ1uft3xho5_r1_1280.png"/>
</div>

--- 

### 3. 其他功能

（1）**编辑书籍**：只能编辑 EPUB 格式书籍
<div style="text-align:center">
<img src="https://40.media.tumblr.com/72ce33cfca24e22508e7ca30086e88f1/tumblr_nw525hiyZQ1uft3xho6_r1_1280.png"/>
</div>

（2）**获取书籍**：搜索外文书比较好，搜索资源表中无中文书资源提供方。搜索到的书籍，只有显示绿锁的可以下载
<div style="text-align:center">
<img src="https://41.media.tumblr.com/32263d9c948f6e19005303c341f894e5/tumblr_nw525hiyZQ1uft3xho8_r2_1280.png"/>
<img src="https://41.media.tumblr.com/7741507a0bc6f25286c57ca6f1c3fc75/tumblr_nw525hiyZQ1uft3xho9_r1_1280.png"/>
</div>

---

**参考资料：**

**[李凡希博客](http://www.freemindworld.com/blog/2010/101022_calibre_tips_and_faq.shtml)**

**[Calibre 電子書轉檔、編輯、閱讀一應俱全，還可將電子書傳送到Kindle](http://tfeng.org/?p=5979)**

**[calibre User Manual](http://manual.calibre-ebook.com/)**

*总结完毕，持续更新......*







