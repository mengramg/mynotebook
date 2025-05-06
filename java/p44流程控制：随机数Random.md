## 案例技术：生成随机数

### Random的使用

+ 作用：生成随机数

得到0-9的随机数的实现步骤

1. 导包：告诉程序去JDK哪个包中找Random
2. 写一行代码拿到随机数对象
3. 调用随机数的功能获取0-9之间的随机数

```java
	package com.mengjiaze.random; 
	import java.util.Random;	//1导包
	public class Test{
        public static void main(String[] args{
            Random r = new Random();
            int data = r.nextInt(10); 
            System.out.println(data);
        }
    }
```

#### Random生成指定区间随机数

技巧：减加法

==步骤==

1. 用减法将区间开始的值改为0开始
2. 再将减去的数加回来

+ eg：生成1-10之间的随机数

```java
	Random r = new Random();
	int number = r.nextInt(10)+1;	//1-10
```

==3-17随机数==

1. 先减3，区间变为0-14
2. 再把减去的3加回来

代码如下

```
	r.nextInt(15)+3
```

小技巧：在idea中ctrl+alt+t可以对代码进行包围