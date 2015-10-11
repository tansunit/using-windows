# 安全防护

### 1. 安全防护的必要性

如果把 Windows 系统及电脑上的资料比作人体，安全防护就相当于免疫系统，而防护软件和免疫系统中的吞噬细胞、皮肤相似。

一个没有免疫系统的人体，难免经常生病。

当然，人体自觉地远离病原体也是自我防护，而且这种意识有必要十分强烈。我们使用电脑、手机同样应当具备辨识有害文件的意识、基本技能。

--- 
### 2. 防毒软件——[Avast!](https://www.avast.com)


* 确保系统上没有同时运行两种杀毒软件。如果现在正使用其他杀毒软件，想把杀毒软件换成 avast!，一定要在安装 avast! 前先卸载其他杀毒软件。

* 新的恶意程序和病毒总是在不断产生，所以一定要及时更新 avast! 的病毒数据库以保护计算机。

 <div style="text-align:center">
 <img src="https://40.media.tumblr.com/ca680a2305f3a668d8224edee9ff0c59/tumblr_nw082xxS1X1uft3xho3_1280.png"/>
 </div>

## 

#### 2.1 注册

**注册可长期免费使用，默认使用30天。**
<div style="text-align:center">
<img src="https://40.media.tumblr.com/9602acc2dcd6001505ea084c7c037435/tumblr_nw082xxS1X1uft3xho1_1280.png"/>
<img src="https://41.media.tumblr.com/0fc5f82a7d3d749f3a4b85f007bed2ca/tumblr_nw082xxS1X1uft3xho2_500.png"/>
</div>

## 

#### 2.2 更新病毒库、应用

在【设置】--【更新】设置为自动更新病毒库、程序。

<div style="text-align:center">
<img src="https://40.media.tumblr.com/a6f1ab9493d2ce7aa484eaf90b78ed9b/tumblr_nw082xxS1X1uft3xho5_1280.png"/>
</div>

## 

#### 2.3 扫描、处理染毒文件

用 Avast! 处理恶意软件和其他病毒有两个主要步骤。第一步扫描您的电脑并检测出威胁。第二步是删除或是将病毒移入到Avast! 病毒隔离区。

**（1）扫描病毒有五种方式：**

* **快速扫描：**在用户时间比较紧的情况下，推荐此项来检测潜在的或可疑的威胁。

* **完整的系统扫描：**在用户充足的情况下，推荐使用此项来执行一次对系统的彻底扫描。如果您在计算机上第一次使用杀毒软件，也推荐使用此项。此扫描所需要的时间取决于计算机上的文件、文件夹和硬盘的数量及计算机的速度。

* **可移动媒体扫描：**在扫描外置硬盘、USB闪存和其他媒体，**特别是在这些媒体在其他公用设备上使用过，推荐使用此项**。它将扫描所有的可移动设备上会在设备连接时自动运行的有害程序。

* **选择要扫描的文件夹：**在扫描单个或多个文件夹时，特别是当怀疑某个文件或文件夹被感染时，推荐使用此项。

* **开机扫描**：可以在 Windows 操作系统开始运行前进行全面的硬盘扫描。在开机扫描进行的时候，大多数的恶意软件和病毒仍然处于停止状态，因为它们还没机会被激活运行或与其他系统进程进行交互，这时可以更容易发现和清除病毒。

 * 开机扫描可以直接读取硬盘，同时避开加载 Windows 的驱动程序和文件系统，这往往是大多计算机病毒最喜欢的攻击目标。这样可以扫描出最顽固的「rootkits」类型病毒——一种极其危险的恶意软件。即使在只是有点怀疑计算机系统有可能被感染时，也**推荐进行开机扫描**。

**（2）处理病毒**

一般，扫描中识别到的病毒会自动放到**隔离区。**

* 1）打开**扫描结果**
<div style="text-align:center"> 
<img src="https://41.media.tumblr.com/77b19f1c7d0e4279c633fe3e2786d405/tumblr_nw082xxS1X1uft3xho7_1280.png"/>
</div>

* 2）点击**操作/针对所有应用此操作**打开下处理病毒的下拉菜单
 
 * **修复：**这个选项会尝试修复被感染的文件。

 * **移入隔离区**：直接将病毒移到隔离区，与其他正常文件分开。

 * **删除：**被感染文件将会被永久删除。

 * **自动修复**：尝试修复文件，失败会继续转入隔离区。

 * **不采取任何处理：**这个选项顾名思义，**绝对不推荐在处理有潜在危害的恶意软件或病毒时使用此项**。

## 

#### 2.4 使用病毒隔离区

当病毒被移入 Avast! 病毒隔离区后，就可以从容不迫地考虑如何处理这些病毒了。

**（1）由下图所示位置进入病毒隔离区**
<div style="text-align:center">
<img src="https://41.media.tumblr.com/2345af080a43c68c30a1a9f3b52e900a/tumblr_nw082xxS1X1uft3xho8_r1_1280.png"/>
</div>

**（2）右键需处理的病毒文件**
<div style="text-align:center">
<img src="https://40.media.tumblr.com/df7d485955b8e36864b0088a9b93226b/tumblr_nw082xxS1X1uft3xho9_1280.png"/>
</div>

* **删除：**此项将不可恢复地删除病毒文件。

* **还原：**此项将把病毒还原到它最初的存储位置。

* **恢复并添加到排除项中：**若确认该文件不是病毒/没有被病毒感染，可恢复文件继续使用。

* **提取：**此项将把文件或病毒复制到您指定的位置。

* **扫描：**此项将在下一次扫描重新提交该病毒。

* **提交至病毒实验室……：**此项将向已知病毒数据库提交病毒样本以进行深入分析。选择此项将打开一个提交表格，需要您填写然后发送。

* **属性：**此项将会显示关于此病毒的更多细节信息。

* **添加……：**使用此项可以浏览您的系统，并将您想要添加的文件移入病毒隔离区。此功能非常有用，当您在被突发病毒袭击时可以用来保护您的重要文件。

* **刷新全部文件：**此项将更新您的文件列表，这样您就可以看到最新的文件。

**注意：双击病毒隔离区中的病毒并不会激活或运行病毒，而只会显示病毒属性或是您在弹出菜单中查看属性时相同的信息。**

--- 
### 3. 防火墙——Windows 自带

对 Windows 用户而言，直接用 Windows 自带的防火墙，基本上就能满足需求。

**设置方法：**在【控制面板】——【系统和安全】——【Windows 防火墙】设置，如需要禁止某些程序通过防火墙，取消最前面的选勾。

<div style="text-align:center">
<img src="https://40.media.tumblr.com/2d030bbe499f630fba1266cbf6bafe0e/tumblr_nw09duZXzZ1uft3xho1_1280.png"/>
</div>

---
### 4. 拉黑 CNNIC 证书

#### 4.1 CNNIC 是什么东西？

CNNIC 全称是 China Internet Network Information Center,中文叫「中国互联网信息中心」。是中国对互联网进行管理的一个机构。

但是，对于电脑来说，CNNIC 是一个伪装的很好的坏人，可以伪造网络通行证证书骗取信任，与其他东西狼狈为奸。

更多关于 CNNIC 的危害，请看

[CNNIC到底干了啥事？](https://program-think.blogspot.com/2010/02/remove-cnnic-cert.html#head-1)

[这事儿对咱有啥影响？](https://program-think.blogspot.com/2010/02/remove-cnnic-cert.html#head-2)

## 

#### 4.2 从系统中拉黑可疑证书

工具：[RevokeChinaCerts](https://github.com/chengr28/RevokeChinaCerts)

1. 在线证书吊销——针对部分网站
  
 （1）下载工具并打开，双击```RevokeChinaCerts_Online.bat``` 运行 ，输入 **2**
 
 <div style="text-align:center">
 <img src="https://41.media.tumblr.com/e42d596db1ca63f1d0b569311b46e272/tumblr_nw0byvzrOk1uft3xho1_1280.png"/>
 </div>

  （2）等待执行完毕，按任意键。
  
 <div style="text-align:center">
 <img src="https://41.media.tumblr.com/fe4326abe3c891a849881d276228b89e/tumblr_nw0byvzrOk1uft3xho2_540.png"/>
 </div>
 
**说明：**运行时如果遇到 ```Error: Can not find a certificate matching the hash value``` 或 ```Failed to save to the destination store```  等不需要在意，只要添加吊销证书时出现 **CertMgr Succeeded** 即可。
 
2. 屏蔽某些软件运行、部分组织和企业的证书

 （1）在同一个文件中，双击运行```RevokeChinaCerts_CodeSigning.bat```或 ```RevokeChinaCerts_Organization.bat```。输入** y **并确定。
 
 <div style="text-align:center">
 <img src="https://40.media.tumblr.com/4cdb388b0bd678c792701d344fba6669/tumblr_nw0byvzrOk1uft3xho3_1280.png"/>
 </div>
 
 （2）继续输入 **1 **，看到类似下图，说明执行成功。
 
  <div style="text-align:center">
  <img src="https://40.media.tumblr.com/561445c9d5b37083487c74d2158a3026/tumblr_nw0byvzrOk1uft3xho4_1280.png"/>
  </div>

## 

#### 4.3 清理 IE、Chrome 不信任证书

1. 运行 Windows 的证书管理器（```Winkey+R``` ,执行 **certmgr.msc**）。

2. 选中「受信任的根证书颁发机构」=>「证书」。

3. 查看右边的证书列表。如果里面已经有 CNNIC 的证书，直接跳到第7步。

4. 先翻墙到下面的链接下载现成的CNNIC证书（要解压缩出来）。

5. 鼠标在「受信任的根证书颁发机构」=>「证书」上点右键。在右键菜单中点「所有任务」=>「导入」。

6. 出现一个导入向导，根据先导一步步的提示，把上述 CNNIC 证书导入到证书列表中。

7. 选中 CNNIC 证书，点右键。在右键菜单中点「属性」。

8. 在跳出的属性对话框中，选中「**停用这个证书的所有目的**」，然后确定。

9. 最后，为了保险起见，再把这三个证书，导入到「不信任的证书」中（方法和上述类似）。

## 

#### 4.4 清理 Firefox 可疑证书

不论是在哪个操作系统下，只要你用的是 Firefox 浏览器（它的证书体系独立于操作系统的），则需要执行如下步骤：

1. 从菜单「工具」=>「选项」 ，打开选项对话框。

2. 切换到「高级」部分，选中「加密」标签页，点「查看证书」按钮。

3. 在证书对话框中，切换到「证书机构」。

4. 里面的证书列表是按字母排序的。把 CNNIC 打头的都删除。

**注：如果某个证书是 Firefox 自带的，则删除之后，下次再打开该对话框，此证书还在。不过不要紧，它的所有「信任设置」，都已经被清空了。**

## 

#### 4.5 清理门户完毕，验证是否成功

为了保险起见，在完成上述的清除工作之后，需要用浏览器访问一下 https://www.cnnic.cn （记得用 **HTTPS** 协议哦）。

如果浏览器报告该网站的证书有问题，那恭喜你，你的门户清理干净了。
反之，就要重新检查一下，看上述操作是否出了差错。

<div style="text-align:center">
<img src="https://41.media.tumblr.com/3882a3308dc604705b2f272fbd57f224/tumblr_nw0byvzrOk1uft3xho5_r1_1280.png"/>
</div>

--- 
### 5. 如何设置密码

#### 5.1 看看反面教材——脆弱密码

* **密码和用户名一样**

* **密码是一串简单数字**

 * 连续数字串（顺序/逆序）
 * 规律性变化的数字串（奇偶数）


* **密码太短**

 如果你的密码小于6个字符，很容易被暴力破解。

* **用简单英文单词作密码**

* **用日期作密码**

 最常见的是以生日日期作重要密码。
 
## 

#### 5.2 不共用口令/密码

编者发现有相当多的用户喜欢靠一个密码包打天下。这是相当相当危险的事情。同一个密码，用的场合越多，则泄密的危险越大。而一旦泄露，你的安全防线就会全面崩溃。

不要在所有（大多数）场合使用同一个口令。由于共用口令存在很大的风险，比较稳妥的办法就是——每一个场合仅使用一个密码。但是很多人会抱怨说：这样会很繁琐，增加了很多的麻烦。对密码分级设置是一种不错的方式。

根据[二八原理](https://en.wikipedia.org/wiki/Pareto_principle)，非常重要口令毕竟只占少数。所以，就像电影要有分级机制一样，你的密码/口令也要引入分级的概念。通过分级机制，对大多数不太重要的口令，可以采取简化的安全措施；而对少数重要的口令，采取高度安全的措施。

## 

#### 5.3 密码分级

* **第1级：不重要的口令**

所谓不重要的口令，是万一被盗或者忘记了，对你没啥损失。
一般，那些需要注册才能下载资料的临时网站，临时注册一个账号，然后登录上去下载东西。这类账号，基本上都属于一次性的（用完即扔），所以重要程度很低。也可以同一个临时帐号用于若干类似的网站。

**基本上不用考虑太多安全性的因素。随便设置一个即可。**


* **第2级：重要但少用的口令**

对于重要的口令，还要根据其使用的频繁程度，再区别对待。有些口令虽然重要，但是使用的频度很低。由于这类口令很少使用，所以设置得麻烦一些，问题也不大。


* **第3级：重要且频繁使用的口令**

比如银行帐号、金钱交易的密码，邮箱密码。

不要将正在使用的手机号码或者生日日期设置为这类号码。

## 

#### 5.4 如何设置高安全度密码

复杂是对别人而言，对自己来说要简单。否则，很容易混乱、忘记。

（1）**用多个单词构成词组**——可以考虑由2-5个英文单词构成密码。如果你英语不灵光或比较习惯中文，也可以考虑用2-5个汉字的拼音来构成密码。

*能显著增加密码长度。可能需要改变记忆密码的习惯。密码中只有字母，复杂度不够高。*

（2）**插入特殊字符**——比（1）再复杂些，可以在单词或汉字拼音之间插入一些特殊字符。最常见的有空格、下划线、减号、斜杠、星号等。

（3）**字符变换：用形状类似的字母和数字进行相互替换。**

* 常见的变换有如下几种：（仅供参考）

 字母 o 和 数字 0

 字母 l 和 数字 1

 字母 z 和 数字 2

 字母 s 和 符号 $

 字母 g 和 数字 9

 字母 q 和 数字 9

 字母 a 和 符号 @

 字母 b 和 数字 6

 字母 x 和 符号 *

不用改变原先的记忆习惯。

（4）**键位平移**——在进行键盘输入时，把手**向右**平移一个键位。通常咱们在盲打时，两只手的食指分别对着字母F和字母J。平移之后，则食指对着G和K。

*不用改变原来的记忆习惯。依赖于 QWERT 键盘分布，如果在九宫格键盘里要输入密码，就略有难度了。*

（5）**巧用 Shift 键**——密码中有部分字符是数字，输入时按住 SHIFT 键会让这些数字字符变为特殊符号。

（6）**运用数学等式**——比如：110+9=119  其中有数字和特殊符号。
也可以把数字用英文表示，如：two+7=nine

*密码同时包含字母、数字、特殊符号。高度复杂。需要改变记忆习惯。*

--- 

### 6. 管理密码——[KeePass](http://keepass.info/) （最新版：2.3.0）

#### 6.1 更改界面为中文

（1）进入 http://keepass.info/translations.html ，找到相应的 KeePass 中文简体语言包下载文件。

*1.29+适用于 KeePass 1.x 版本，2.30+适用于 KeePass 2.x 版本。*

<div style="text-align:center">
<img src="https://41.media.tumblr.com/9fcfdd7e7550c54f1230a4fba4e995e7/tumblr_nw0is68YrH1uft3xho1_1280.png"/>
</div>

（2）解压缩语言包文件，将里面的语言文件移动到 KeePass 安装文件内，与 KeePass.exe 处于同一文件中。

<div style="text-align:center">
<img src="https://41.media.tumblr.com/29c381fab8ddcc29ffa3575f1568a824/tumblr_nw0is68YrH1uft3xho2_r1_1280.png"/>
</div>
*（如图，Chinese_Simplified.lngl 是我下载的语言文件）*

（3）启动 KeePass （若处于开启状态，需关闭重新打开），从 **View 菜单**进入** Change Language** 项，选择添加的中文语言，重启 KeePass

## 

#### 6.2 新建密码数据库

（1）启动 KeePass , 选择 **文件**--**新建**

<div style="text-align:center">
<img src="https://40.media.tumblr.com/2dda887c5a01d44b772f7d51ecc54648/tumblr_nw0is68YrH1uft3xho3_r1_1280.png"/>
</div>

(2)设置密码数据库存放位置、密码数据库文件命名（一般默认即可，方便日后找）

<div style="text-align:center">
<img src="https://40.media.tumblr.com/20c436a673d31cb4cbc4a4364dc2c023/tumblr_nw0is68YrH1uft3xho4_r1_1280.png"/>
</div>

（3）设置**独一无二的管理密码。**

* 通过手动输入【管理密码】或添加【密钥文件】设定。
* 手动输入的管理密码要记住，或者添加的密钥文件不能丢失。
* 【管理密码】和【密钥文件】可同时使用，双重加密。*（一般，单项强度高的密码足够）*
* 不建议使用第三种【Windows 用户帐号】。
* 输入密码时，随着使用的密码字符位数的增加，密码的强度或完整性越好，黄绿色的进度栏越偏向绿色部分。**应尽量达到绿色部分的一半左右位置。**

 <div style="text-align:center">
 <img src="https://40.media.tumblr.com/b1b25ac8dfe93d2fb79fc19d1b09c0c2/tumblr_nw0is68YrH1uft3xho5_r1_540.png"/>
 </div>
 
（4）密码数据库配置
 
* **常规：**根据自己喜好设置密码数据库名称、简短描述、颜色
<div style="text-align:center"> 
<img src="https://40.media.tumblr.com/147b19ee441ac44fb870e2310d231a93/tumblr_nw0is68YrH1uft3xho6_r1_500.png"/>
</div>
 
* **安全：**默认设置
<div style="text-align:center"> 
<img src="https://41.media.tumblr.com/6eeef55da8c28401cdff878649e4bab5/tumblr_nw0is68YrH1uft3xho7_r2_500.png"/>
</div>
 
* **压缩：**默认设置
<div style="text-align:center"> 
<img src="https://41.media.tumblr.com/ca5e55eb489dfe3bc461f0e1d1506e01/tumblr_nw0is68YrH1uft3xho8_r1_500.png"/>
</div>
 
* **高级：**如需要过段时间更改密码，可以勾选并设置时间间隔。
<div style="text-align:center"> 
<img src="https://41.media.tumblr.com/bb59be10228b6f8dbf5ddd6cbad71122/tumblr_nw0is68YrH1uft3xho9_r1_500.png"/>
</div>
 
（5）保存密码数据库
 
 **文件**——**另存为**——**选择至文件**——保存位置、命名文件
<div style="text-align:center"> 
<img src="https://40.media.tumblr.com/dcac30a50f3bd9d71dd0272e30f1ad5f/tumblr_nw0is68YrH1uft3xho10_r1_1280.png"/>
</div>
 
## 

#### 6.3 添加密码数据库（以电子邮件密码数据库添加为例）

（1）点击【电子邮件】，再点击下图圈出的钥匙
 <div style="text-align:center">
 <img src="https://40.media.tumblr.com/d88938fa7e337413dd94248b510a2187/tumblr_nw0k1qLBHx1uft3xho1_1280.png"/>
 </div>
 
 （2）填写相关信息

* ** 1）记录**

 * **标题**：描述密码是谁的。如 Gmail 密码。
 
 * **图标**：更改/自定义与该记录相关的图标。

 * **用户名**：与密码项目相关的用户名，例如：securitybox@gmail.com (mailto:securitybox@gmail.com) .

 * **密码**：可自动随机生成（如果是注册一个新的邮箱账号，可以使用该字段的**随机生成**。也可以使用自己的密码代替默认密码，用于添加已有帐号情况下。
 
 * **网址**：与密码相关的网站，例如：https://mail.google.com (https://mail.google.com/) 

 * **失效**：可自定义该密码失效时间，提醒自己重置密码。（定期更改密码是完全有必要的！**好的安全措施是每三个月或半年改变一次密码**）

 <div style="text-align:center">
 <img src="https://40.media.tumblr.com/5c25ec42e2f6e4ec58a58a68f3593cb1/tumblr_nw0k1qLBHx1uft3xho2_500.png"/>
 <img src="https://40.media.tumblr.com/c90d6f64559d79d3e87edf6a13a8894c/tumblr_nw0k1qLBHx1uft3xho3_540.png"/>
 </div>
 
* **2）属性**

 * 自定义前景色、背景色：如下图，设置前景色为红色（效果如下图）
 * 替代 URL ：如下图，设置通过 Chrome 打开邮箱
 
<div style="text-align:center"> 
<img src="https://41.media.tumblr.com/c7268e27421de7adca67ad6a019f70b4/tumblr_nw0k1qLBHx1uft3xho4_500.png"/>
<img src="(https://41.media.tumblr.com/9e5109f6f4d7f7ee857f0e57a3cfc019/tumblr_nw0k1qLBHx1uft3xho5_1280.png"/>
</div>

## 

#### 6.4 退出、重新进入 KeePass

* 退出：直接关闭管理窗口，若提醒保存更新，可勾选**退出和锁定数据库时自动保存**
 
<div style="text-align:center"> 
<img src="https://41.media.tumblr.com/0e3750ea2439bf00b30ae1dbed53bf48/tumblr_nw0k1qLBHx1uft3xho6_500.png"/>
</div>

* 重新进入：需输入管理密码

 <div style="text-align:center">
 <img src="https://41.media.tumblr.com/c73775c928564fafc6adeabc955e86d7/tumblr_nw0k1qLBHx1uft3xho7_r1_500.png"/>
 </div>

---  
 **参考资料：**

1. **[List of Password Managers](https://en.wikipedia.org/wiki/List_of_password_managers)**
2. **[如何安装和使用 KeePass](https://info.securityinabox.org/zh/using_keepass)**


*此篇保持更新......*

