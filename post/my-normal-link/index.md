
[Java Collection 移除元素的几种方式](https://juejin.cn/post/6844904035766501384)

'''  

for (int i = 0; i < aList.size(); i++) {
if ("abc".equals(aList.get(i))) {
aList.remove(i--);// 索引回溯
}  

'''

[i++不是原子运算](https://www.jianshu.com/p/a47b141452ce)  [为什么不是原子操作](https://blog.csdn.net/qq_35425070/article/details/83866209)

    内存屏障是个CPU指令,Java内存模型中volatile变量就是通过在写操作之后会插入一个store屏障，在读操作之前会插入一个load屏障，来实现的“禁止指令重排序”

[CAS 原子操作](https://juejin.cn/post/6844904177856937991)
    cmpxchg指令，lock前缀指令执行时，要么锁住 “总线锁”，要么锁住 “缓存锁”，目的都是为了保证 “比较、交换” 这个复合操作的原子性

[java线程池](https://tech.meituan.com/2020/04/02/java-pooling-pratice-in-meituan.html)

[rpc框架](https://www.jianshu.com/p/28e48e5f9c73)

[@Autowired底层实现](https://juejin.cn/post/6844903957135884295)

[和为定值k的子数组长度](https://blog.csdn.net/study_000/article/details/77524798)

[mysql与redis数据同步](https://www.cnblogs.com/gered/p/11737388.html)

[异步io、NIO、AIO](https://blog.csdn.net/weixin_43122090/article/details/105462088)

[G1垃圾收集器](https://tech.meituan.com/2016/09/23/g1.html)

[volatile原理](https://zhuanlan.zhihu.com/p/77085695)

[JVM内存模型](https://www.cnblogs.com/chenyangyao/p/5269622.html)

[java8 ArrayList](https://zhuanlan.zhihu.com/p/34443888)

[虚拟机垃圾回收](https://www.infoq.cn/article/zoyqri4c-bfkmubmzmkn)

[对B+树，B树，红黑树的理解](https://www.jianshu.com/p/86a1fd2d7406)

[浅谈AVL树,红黑树,B树,B+树原理及应用](https://blog.csdn.net/whoamiyang/article/details/51926985)

[B+树详解](https://ivanzz1001.github.io/records/post/data-structure/2018/06/16/ds-bplustree)

[Synchronize和ReentrantLock区别](https://juejin.cn/post/6844903695298068487)

[深入理解ReentrantLock的实现原理](https://juejin.cn/post/6844903805683761165)

[Redis 跳跃表]()


[Redis 字符串实现](https://redisbook.readthedocs.io/en/latest/internal-datastruct/sds.html)

[线程里该如何返回值 callable runnable]()

[ThreadLocal volatile 线程的内存模型]()










