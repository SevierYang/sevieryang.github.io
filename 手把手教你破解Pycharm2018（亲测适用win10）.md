
# **手把手教你破解Pycharm2018（亲测适用win10）**


作为一名玩蛇客，少不了一个好用的IDE。而好用的IDE就像是一把利剑，剑客武功再高，狭路相逢之时也需亮出宝剑。
本人电脑安装过PyCharm和Sublime，这次mark down一下安装PyCharm的过程。

## 一.破解大致步骤：



1.下载PyCharm 2018及补丁文件JetbrainsCrack-2.8
2. 将下载好的补丁放在PyCharm安装目录下面的bin文件夹下面
3. 修改bin文件夹下面的配置文件
4. 修改系统的hosts文件
5. 获取注册码
6. 重启PyCharm，成功！

 [^1]: [mermaid语法说明](https://mermaidjs.github.io/)







## 二.每个步骤详解:

### 1.  下载PyCharm 2018及补丁文件JetbrainsCrack-2.8
1） 通过百度网盘下载，链接如下：
链接：https://pan.baidu.com/s/1Ct2SkW1xBuUYZgmYxFNcgQ 
提取码：a1qx 
2） 截图如下：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181101063617458.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyNDQyMzY5,size_16,color_FFFFFF,t_70)


### 2. 将下载好的补丁放在idea的安装目录下面的bin文件夹下面
截图如下:
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181101063636919.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyNDQyMzY5,size_16,color_FFFFFF,t_70)
 
### 3. 修改bin文件夹下面的配置文件
1）找到bin目录下的PyCharm.exe.vmoptions和PyCharm64.exe.vmoptions用记事本打开，在最后一行添加：
-javaagent:C:\Program Files\JetBrains\PyCharm 2018.2.4\bin\JetbrainsCrack-2.8-release-enc.jar
记得要加补丁文件名包括后缀，注意是两个文件！ 
2）截图如下：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181101063649454.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyNDQyMzY5,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181101063704280.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyNDQyMzY5,size_16,color_FFFFFF,t_70)






### 4. 修改系统的hosts文件
Windows系统hosts文件路径为：c:\windows\system32\drivers\etc
将0.0.0.0 account.jetbrains.com添加到hosts文件最后。
截图如下：![在这里插入图片描述](https://img-blog.csdnimg.cn/20181101063726788.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyNDQyMzY5,size_16,color_FFFFFF,t_70)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20181101063740696.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyNDQyMzY5,size_16,color_FFFFFF,t_70)



### 5. 获取注册码
注册码地址：http://idea.lanyus.com/
启动PyCharm，当需要激活时，选择activation code，复制注册码到Acrivation code中的空白处，点击OK 
截图如下：
![在这里插入图片描述](https://img-blog.csdnimg.cn/2018110106380790.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyNDQyMzY5,size_16,color_FFFFFF,t_70)

### 6. 重启PyCharm，安装成功!


### 7. 查看激活码的有效期
打开help——about
截图如下：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181101063831792.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyNDQyMzY5,size_16,color_FFFFFF,t_70)




