# python-data-science

本课程会教大家如何使用Python分析和可视化数据，开启Data Science职业之旅。

本课程是Python for Data Science的入门课程，是学习Text Mining，Machine Learning，Deep Learning的基础。

主要包含以下內容：

# 一、anaconda和Jupyter的介绍和安装

## 介绍

![1629552401916](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629552401916.png)

![1629552501963](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629552501963.png)

![1629552526524](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629552526524.png)

![1629552582725](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629552582725.png)

![1629552610246](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629552610246.png)

![1629552626309](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629552626309.png)

![1629552655543](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629552655543.png)

![1629552669095](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629552669095.png)

![1629552730213](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629552730213.png)

![1629552750225](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629552750225.png)

![1629552771493](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629552771493.png)

![1629552796168](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629552796168.png)

![1629553027058](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629553027058.png)

![1629553053087](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629553053087.png)

![1629553180788](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629553180788.png)

![1629553206835](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629553206835.png)

![1629553252456](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629553252456.png)

## 安装

**mac**

下载后图形安装/命令行安装(选图形)

![1629553406093](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629553406093.png)

最好不要修改默认路径(why)

![1629553508709](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629553508709.png)

进入bin

![1629553703258](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629553703258.png)

查看所有包

![1629553740090](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629553740090.png)

启动 jupyter notebook server

![1629553799164](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629553799164.png)

新建notebook

**window**

![1629553911585](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629553911585.png)

点击jupyter notebook （找一找）

**linux**

复制下载链接 wget 命令

![1629554049957](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629554049957.png)

回车

![1629554093295](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629554093295.png)

回车

![1629554119589](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629554119589.png)

![1629554145377](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629554145377.png)

不打开浏览器

![1629554215318](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629554215318.png)

解决远程访问的问题(不只是本地)

端口转发：

![1629554325916](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629554325916.png)

后面的和人家不一样@root +ip地址 （hostname）

访问localhost:8888

**jupyter notebook**

![1629554425887](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629554425887.png)

![1629554496570](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629554496570.png)

从当前目录打开

![1629554540418](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629554540418.png)



# 二、numpy入门

## 2.1数据科学领域5个常用库

![1629690742521](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629690742521.png)

![1629690792267](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629690792267.png)

![1629690819632](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629690819632.png)

![1629690849090](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629690849090.png)

![1629690881496](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629690881496.png)

![1629691036612](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629691036612.png)



## 2.2数学基础回顾之矩阵运算

![1629691204113](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629691204113.png)

![1629691227021](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629691227021.png)

![1629691244162](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629691244162.png)

![1629691260938](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629691260938.png)

![1629691282964](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629691282964.png)

![1629691312105](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629691312105.png)

## 2.3Array的创建及访问

## 2.4数组与矩阵运算

## 2.5Array的input和output

# 三、pandas入门

![1629707640576](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629707640576.png)

# 四、使用numpy+pandas进行数据分析和处理

# 五、数据可视化：matplotlib入门

![1629820417277](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629820417277.png)

![1629820527365](C:\Users\小傲娇\AppData\Roaming\Typora\typora-user-images\1629820527365.png)

# 六、项目实战

