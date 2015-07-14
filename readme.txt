Git is a version control system
Git is free software
 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

1 

：

FIFO

，

first in first out

，这个是大家最熟的，先进先出。

 

 

2 

：

LFU

，

 

Less 

Frequently 

Used

，就是上面例子中使用的策略，直白一点就是讲一直以来最少被使用

的。如上面所讲，缓存的元素有一个

hit

属性，

hit

值最小的将会被清出缓存。

 

 

3 

：

LRU

，

Least Recently Used

，

最近最少使用的

，缓存的元素有一个时间戳，当缓存容量满了，而又

需要腾出地方来缓存新的元素的时候，

那么现有缓存元素中时间戳离当前时间最远的元素将

被清出缓存。

 