# Terry博客

## 第一章 多线程并发编程

### 1.1 java程序运行原理
![JVM内存模型](https://github.com/xl0139/blog/blob/master/JVM%E5%86%85%E5%AD%98%E6%A8%A1%E5%9E%8B1.jpg)
#### 方法区：
  JVM用来存储加载类的信息、常量、静态变量、编译后的代码等数据
  这是虚拟机规范中的一个逻辑区划。具体实现根据不同虚拟机来实现
  如：Oracle hotSpot 在java7中方法区放在永久代，java8 中放在元数据空间
