# 磁盘使用

### 1. 磁盘匪类

C 盘：一般作系统盘，Windows 系统文件都在里面，电脑桌面也属于一份子。

D/E 盘：非系统盘，存放各种软件、文件。

--- 
### 2. C 盘使用注意项

1. **C 盘产生的垃圾**

 1. 各种软件使用的一些缓存，保存在_ C:\Users\xxx\AppData\Local\Temp_ ；

 2. 垃圾箱里的东西。
 
2. **C 盘内存占用太多**

 1. 桌面文件太多，尤其一些大文件；
 2. 垃圾箱长期不清空;
 3. 软件使用缓存太多;
 4. 各种软件都安装（下载）在 C 盘。
![image1](https://41.media.tumblr.com/a1a602efd34c99032ff603ebbe2c2b15/tumblr_nvybt5Eg671uft3xho7_1280.png)
*（密集恐惧感袭来）*

--- 
### 3. C 盘优化

1. **C 盘磁盘清理**
 1. 右键 C 盘进入**属性**，点击**磁盘清理**
![image2](https://40.media.tumblr.com/374fd3b80e6d8b57bf372162d0ed8cbf/tumblr_nvybt5Eg671uft3xho1_400.png)
 
 2. 待扫描完毕弹出对话框，勾选「要删除的文件」所有条目，**确定**，清理垃圾。
![image3](https://41.media.tumblr.com/9fd15a3a52a49240f7d2b2e967721d19/tumblr_nvybt5Eg671uft3xho2_r1_400.png)

2. **清理电脑缓存**
 1. Winkey+R ，出现【运行】对话框，输入**```%temp%```**，【确定】。
![image4](https://41.media.tumblr.com/7bd96bf01cc8e1e970d0ed1db63ae14c/tumblr_nvybt5Eg671uft3xho3_500.png)
 
 2. 进入```C:\Users\xxx\AppData\Local\Temp```文件夹。选择全部文件（夹），删除。提醒某文件正被使用时，【跳过】即可。
![image5](https://41.media.tumblr.com/4620213add359186734f66e6e8d86728/tumblr_nvybt5Eg671uft3xho4_r1_1280.png)

3. **磁盘碎片整理**
 1. 从【控制面板】进入【对硬盘进行碎片整理】
![image6](https://41.media.tumblr.com/b983836b0f133b1678f9c13a3af0994a/tumblr_nvybt5Eg671uft3xho5_1280.png)
 
 2. 在【磁盘碎片整理程序】中选择 C 盘，先【分析磁盘】，结束后进行【磁盘碎片整理】。
![image7](https://40.media.tumblr.com/d784cde193008b0ae968a040c3455b10/tumblr_nvybt5Eg671uft3xho6_r1_1280.png)
（*备注：此方法也适用于其他磁盘*）