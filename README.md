# summerjournal2015
### 7.11 
* 开始阅读greenlet

>> (http://segmentfault.com/a/1190000000723209)[greenlet源码阅读]
>> (https://code.google.com/p/libhjw/wiki/notes_on_greenlet)[greenlet]
>> (http://blog.csdn.net/fjslovejhl/article/details/38824963)[greenlet]

### 7.12
* 停电到PM8::00
* 上午看了一些《离散数学及其应用》，觉得应该找到中文版对照看
* 看了《python网络编程攻略》，书一般，全是例子，没有什么卵用
* 看了**greenlet doc** [http://greenlet.readthedocs.org/en/latest/](greenlet docs)

>>  **define的格式**<br>
>>  // Macro to get a random integer with a specified range <br>
>>  #define getrand
om(min, max) \ <br>
>>  ((rand()%(int)(((max) + 1)-(min)))+ (min))

### 7.13
* 了解到stack和heap的区别
* 阅读关于引用计数相关的文章，完成整理

Python管理内存的三种方法
1. 引用计数器机制
2. 垃圾回收机制
3. 内存池机制

### 7.18
完整看了几篇中文和英文的关于Reference Counting的说明，整理了相关文档
* [Reference Counting in Python](http://edcjones.tripod.com/refcount.html)
* [引用计数、使用C++编写扩展、提供API接口](http://www.incoding.org/admin/archives/808.html)
* [Extending Python with C or C++](https://docs.python.org/3.5/extending/extending.html#reference-counts)

### 7.20
整理了一片关于Reference Count的文章
* [Python引用计数(Reference Count) From 简书](http://www.jianshu.com/p/ecea193abec4)
* [Python Reference Count](https://github.com/hatmouse/summerjournal2015/blob/master/Python%20Reference%20Count.md)

### 7.22
在阅读greenlet的时候，简单阅读了一下如何编写python扩展
### 7.28 7.29.7.30
分析greenlet源码，整理一篇分析文章
