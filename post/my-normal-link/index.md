
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



