# Java第一天

## 1.cmd操作

#### 1.1cmd启动

运行-》cmd or （win + R）

#### 1.2cmd常用命令

盘符 ：切换硬盘

dir 查询当前路径下所有文件

cd 目录 进入单机目录

cd..  回退上一级目录

cd 目录1\目录2 进入多级目录

cd \ 回到根目录

cls 清屏

exit 退出cmd窗口

### 1.3我的电脑快捷键

win+e

### 1.4环境变量配置

意义：可以不需要通过路径，直接从系统默认变量中找到需要启动的文件

我的电脑-属性-高级系统设置-环境变量-system（整个系统，非单个用户）





## 2.java jdk下载

### 2.1 jdk17下载

oracle官网-》![image-20230612153928224](imagesday1\image-20230612153928224.png)

优先下载英文版

进入product

![image-20230612154058936](imagesday1\image-20230612154058936.png)

进入java

![image-20230612154117052](imagesday1\image-20230612154117052.png)

下载纯净安装包

![image-20230612154354941](imagesday1\image-20230612154354941.png)

下载完后的文件最好装在英文目录下，防止后期出现bug

### 2.2 第一个java代码HelloWolrd.java

1.写好一个文件.java

2.通过刚安装好的jdk中的bin文件中的javac.exe编译(javac)

3.java.exe运行(java)(运行时不加后缀名)

## 3.常见案例常见问题

### 3.1标点符号

必须要英文！

区别大小写！

### 3.2手动配置环境变量

目前最新版本jdk安装会自动配置环境变量

![image-20230612163233521](imagesday1\image-20230612163233521.png)

但是如果下载旧版本，则需要手动配置环境变量

1.在系统变量位置新建一个JAVA_HOME

![image-20230612163602448](imagesday1\image-20230612163602448.png)

疑问：为什么不直接装在path里面，而是新建一个JAVA_HOME变量

解析：jdk的bin中有很多其他变量，path为公用路径防止系统更改后，无法运行（以下会有解析）

2.在path中引入新建的变量

![image-20230612163825957](imagesday1\image-20230612163825957.png)

注意变量用%%引用（\bin此为拼接）

### 3.3 java jdk自动配置的工具

![image-20230612164326794](imagesday1\image-20230612164326794.png)

为以上4个

### 3.4部分win10电脑出现bug

部分win10重启后会出现bug，解决方法两种：

1.重装系统

2.直接在path中配置jdk\bin的源目录（治标不治本）（学习情况使用）





## 4.编程工具

#### 4.1高级记事本

subline,notepad++等等

我使用的是notepad++例：

![image-20230612165012145](imagesday1\image-20230612165012145.png)

官网[Notepad++ (notepad-plus-plus.org)](https://notepad-plus-plus.org/)

#### 4.2Notepad++使用说明

编译java文件-》右键选择Edit with Notepad++

第一次编译优先进行编码设置

步骤：1.点击上方设置

2.选择首选项

3.点击新建

4.更改格式

![image-20230612165835768](imagesday1\image-20230612165835768.png)

（编码最好使用ansi：支持中文，日文编码同理选择合适的编码格式）