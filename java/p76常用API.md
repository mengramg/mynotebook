# 常用API

### 包

+ 包是用来管理不同程序，类似于文件夹
+ 建包的语法格式

```
	package com.mengjiaze.mybag;
```

##### 在自己程序中调用其他包下的程序的注意事项

+ 调用自己包的其他程序，可以直接调用
+ 调用其他包的程序，必须导包 ==导包格式：import 包名.类名;==
+ 调用Java提供的程序，也需要导包才可以使用，但Java.lang包下的程序是不需要我们导包的，可以直接用
+ 访问多个程序一样名的其他包，默认只能导入一个程序，另一个程序必须带包名和类名来访问

### String

+ java.lang.String代表字符串

##### 常用String构造器

```
	public String() 创建一个空白字符串对象，不含有任何内容
	public String(String original)根据传入的字符串内容，来创建字符串对象
	public String(char[] chars)根据字符数组的内容，来创建字符串对象
	public String(byte[] bytes)根据字节数组的内容，来创建字符串对象
```

##### String常用方法

![image-20240929164231181](C:\Users\24517\AppData\Roaming\Typora\typora-user-images\image-20240929164231181.png)

##### 注意事项

+ String对象是不可变字符串

（将一个String类型变量加一个字符或者字符串，会产生新的字符串对象，他的地址指向会改变）

+ 双引号给出的字符串对象，存储在常量池中，且内容相同只会存储一份
+ 但是通过new方式创造的字符串对象，每new一次会产生一个新的对象在内存中。

### Arraylist集合

+ 集合是一种容器，用来存放数据，类似于数组
+ 数组定义完成并启动后，长度就固定了，但集合大小可变，开放中用的更多

![image-20240929192517997](C:\Users\24517\AppData\Roaming\Typora\typora-user-images\image-20240929192517997.png)

常用方法

![image-20240929192754153](C:\Users\24517\AppData\Roaming\Typora\typora-user-images\image-20240929192754153.png)

定义Arraylist变量时候可以往后面加尖括号<>表示添加何种类型数据，不加就是void形

eg:ArrayList$<String>$ = new ArrayList$<String>$

