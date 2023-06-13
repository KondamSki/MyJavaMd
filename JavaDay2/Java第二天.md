# Java第二天

## 1.java跨平台

### 1.1java的运行方式

java文件->class文件->平台执行器->虚拟机->处理电脑

![image-20230613161356151](https://github.com/KondamSki/MyJavaMd/blob/main/JavaDay2/imagesday2\image-20230613161356151.png)

### 1.2java跨平台原理

通过虚拟机

![image-20230613161603994](https://github.com/KondamSki/MyJavaMd/blob/main/JavaDay2/imagesday2\image-20230613161603994.png)





## 2.Java的JDK

### 2.1JVM

JVM（java virtual machine）:java虚拟机，真正运行java程序的地方

### 2.2核心类库

### 2.3开发工具

例：javac编译工具，java运行工具等等

（以上3种合起来称为jdk）

![image-20230613162143498](https://github.com/KondamSki/MyJavaMd/blob/main/JavaDay2/imagesday2\image-20230613162143498.png)

### 2.4 JRE

java单独运行的环境不需要一部分开发工具

将剩下的运行工具与前两种打包则组成JRE（比较小）

![image-20230613162410508](https://github.com/KondamSki/MyJavaMd/blob/main/JavaDay2/imagesday2\image-20230613162410508.png)



## 3.java基础概念

### 3.1注释

提示解释说明的信息

//单行注释

/**/多行注释

/****/文档注释



### 3.2关键字

关键字的字母全部小写（编译时会有特殊颜色）

java中大概有50多个关键字

例：class（关键字），表示一个类，后面跟着类名



### 3.3字面量

数据在程序中的书写格式

字面量类型：整数类型、小数类型、字符串类型、字符类型、布尔类型、空类型

![image-20230613164106706](https://github.com/KondamSki/MyJavaMd/blob/main/JavaDay2/imagesday2\image-20230613164106706.png)

ps（制表符\t：可以把前面字符补到8位，方便对齐）



### 3.4变量

在程序执行当中，值可能会发生改变

变量的定义格式：

数据类型 变量名 = 数据值;



### 3.5java中进制的前缀

![image-20230613172432308](https://github.com/KondamSki/MyJavaMd/blob/main/JavaDay2/imagesday2\image-20230613172432308.png)





## 4java的基础语法

### 4.1数据类型

![image-20230613175644406](https://github.com/KondamSki/MyJavaMd/blob/main/JavaDay2/imagesday2\image-20230613175644406.png)

### 4.2标识符

给类，方法，变量起的名字

![image-20230613200245483](https://github.com/KondamSki/MyJavaMd/blob/main/JavaDay2/imagesday2\image-20230613200245483.png)

小驼峰命名法

![image-20230613200752540](https://github.com/KondamSki/MyJavaMd/blob/main/JavaDay2/imagesday2\image-20230613200752540.png)

大驼峰命名法

![image-20230613200904147](https://github.com/KondamSki/MyJavaMd/blob/main/JavaDay2/imagesday2\image-20230613200904147.png)



### 4.3键盘录入

Scanner类

步骤一：导入Scanner包

![image-20230613201248187](https://github.com/KondamSki/MyJavaMd/blob/main/JavaDay2/imagesday2\image-20230613201248187.png)

步骤二：创建对象

![image-20230613201307724](https://github.com/KondamSki/MyJavaMd/blob/main/JavaDay2/imagesday2\image-20230613201307724.png)

步骤三：接受数据

![image-20230613201337205](https://github.com/KondamSki/MyJavaMd/blob/main/JavaDay2/imagesday2\image-20230613201337205.png)

