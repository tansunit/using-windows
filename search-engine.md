# 搜索引擎

### 1. 搜索引擎的选择

有人说「用 Google ,得永生。信百度，变畜牲。」，这句话可能刺中了不少人，但话粗理不粗。

原因有以下几点：

* **搜索结果阉割严重：百度搜索通常看到的的内容很和谐，如同长期看新闻联播。**
* 百度对英文内容收录不如 Google 
* 检索结果相关性很差：搜索结果中第三方链接往往排在前面，官方网站却靠后或者没有。

从检索结果可用性、隐私方面考虑，DuckDuckGo/StartPage/Google 三个搜索引擎是比较好的。

## 

### 2. DuckDuckGo

官网：https://duckduckgo.com 

提供[各大搜索引擎](https://duck.co/help/results/sources)的结果。

<div style="text-align">
<img src="https://41.media.tumblr.com/88edaafedf980b318e983c5d5e6ee3ee/tumblr_nw3hryqLrQ1uft3xho1_1280.png"/>
</div>

## 

### 3. StartPage

官网：https://startpage.com

StartPage 是一个托管在美国和荷兰的服务，通过免费匿名代理提供谷歌搜索和图片搜索结果。相当于一个专门为 Google 定制的 WEB 前端。默认不保存 cookie

与 StartPage 相似的搜索引擎是 [Ixquick](https://www.ixquick.com/) ,来自同一家公司，提供100多个数据源的搜索结果，包括google.

<div style="text-align: center">
<img src="https://41.media.tumblr.com/bdcf702f797c85ce34c57f369930a44c/tumblr_nw3hryqLrQ1uft3xho2_1280.png"/>
</div>

## 

### 4. [Google](https://www.google.com)

**如何禁用「国别重定向」？**

 Google 通常会根据「搜索的 IP 地址」来进行「国别重定向」。
 
 比如使用 Lantern 访问 Google 会直接访问 https://www.google.co.jp 
 要想禁止国别重定向，可以更改地址为 https://www.google.com/ncr

## 

### 5. 搜索技巧

#### 5.1 关键词是入口

使用搜索引擎检索，Key Words 是关键所在。**选择关键词的原则是问题陈述句的名词、动词、形容词**，虚词、语气词不要出现（即使有，也会被忽略），这样搜索的结果相关度比较高。

Key Words 确定，与需要获取信息的目的性有关，分析提出的问题，选择与该问题相关性大的字词。

如果是某个技术故障需要解决，直接搜索错误提示号码（有时需要也设备类型）；还有一类如**想知道猫吃猫薄荷是否有用**，这里的关键词是**猫、猫薄荷。**

如果中文检索不到有效结果，可以换英文检索，李笑来老师说 **Google+Wikipedia+English=Almost Everything** ,英文检索结果往往比中文多、准确、详细（Wikipedia-zh 与 Wikipedia-en 差别就在这里）。

## 

#### 5.2 常用搜索语法

以下搜索技巧主要用于上述三种搜索引擎。

1. **“ ”**：关键词加引号，要求搜索结果中必须包含所有引号中的关键词，尤其搜索一句话出自哪里，如果直接搜这句话，里面的非关键词可能被过滤，如果加上双引号，会自动包含整句话。

2. *****：通配符。指代任何一个词汇。比如「以飨读者」这个成语，第二个字不知道怎么写，也不知道怎么发音——用输入法写不出来。可以用如下语法搜索，就可以找到该成语的写法。**以*读者**（半角输入符号）

3. **+**：关键词以加号连接，要求搜索结果中同时包含这几个关键词。

 **注意：**对网络上出现频率极高的英文，如** i/com/www** 等，及符号 ***/. **作忽略处理，中文搜索会忽略如的/吧/呢这类字词。如果必须用某个常用字词搜索，需要在该字词前输入 + 或者关键词前后用引号。

4. **-**：减号要求搜索结果中包含关键词，但不包含减号后面的关键词。

5. **OR**：有些时候，只想让多个关键词中的一个出现，可以使用 **关键词1 OR 关键词2 **形式搜索。

6. **~ **：紧挨着关键词之前放波浪号表示搜索同义词。如 **~food** ,既可以搜到包含 food 的网页，也能搜到包含 nutrition 的网页。（此处波浪号用半角输入）

7. **..**：两个数字之间放两个小数点表示模糊搜索该数字范围。如**世界杯 2002..2014**；也可以指定一个数字，表示搜索比这个数字大的。

8. **单位换算**：如**100 USD to CNY**；**100 c to f**

9. **related: **：要搜索与指定网站有相似内容的网页，在 **related:**后输入相应网址。

10. **filetype:**：网络上的信息以各种形式存在，有网页文本，图片，DOC，PDF文档，音频，视频，数据库，软件，每种类型的文件都有其对应的一个或多个格式文件。采用 **file:**语法搜索某个类型的文件。如：**互联网 隐私 file:pdf**
<div style="text-align:center">
<img src="https://40.media.tumblr.com/e3d83d9dcb844b42db3bf065453a018d/tumblr_nw3hryqLrQ1uft3xho6_1280.png"/>
</div>
11. **inurl: **：网络中的所有文件和网页都有一个分配到的地址（URL），一般情况下，文件地址是以其文件扩展名结尾的，或者 URL 中包含扩展名。可以通过** inurl:mp3** 找到网络上的 mp3 文件。另外，一些很老的网络空间存储文件用 **index of/**格式，可以用 **index of/ + 关键词** 搜索文件。

12. **site:**：**关键词 site:网址**（*网址不需要写 http://*）。如：** 巨流河 site:pan.baidu.com **

13. **网页缓存：cache:网址**
<div style="text-align:center">
<img src="https://40.media.tumblr.com/5caf6dd14e2bb576b06e3b9ea77ca016/tumblr_nw3hryqLrQ1uft3xho3_1280.png"/>
</div>

**更多......**
<div style="text-align:center">
<img src="https://41.media.tumblr.com/801920a3ed7419ecb30eff22d65aa513/tumblr_nw3hryqLrQ1uft3xho4_1280.png"/>
<img src="https://41.media.tumblr.com/36169ce87f0cf594431cf89847afe624/tumblr_nw3hryqLrQ1uft3xho5_540.png"/>
</div>

**参考资料**：[如何挖掘网络资源[2]：Google 搜索的基本语法](https://program-think.blogspot.com/2013/03/internet-resource-discovery-2.html)


*总结完毕，持续更新......*


