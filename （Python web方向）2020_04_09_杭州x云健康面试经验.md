#### 写在前面

> x云健康主要是做互联网医疗这一块的，问了问团队规模不大，算是小公司吧，从投简历到接到面试通知前后不到2天，没有笔试面，也没问数据结构算法，今天一共面了两面，一面是一个技术专家，感觉年龄相差不是很大，懂得很多，问的东西比较广比较基础，二面是部门领导，大部分聊的是一些关于职业规划之类的，技术方面聊了一个高并发下的缓存和数据库双写一致问题，因为本身不太想从事Python web方向（公司业务主要是java，而python用来做研发支撑的web项目和对速度要求不高的中间件），个人未来更偏向底层或者中间件的开发（偏go或者rust），所以最后谈完也算是结束了，下面总结一下问到的知识点。


#### 一面

##### 网络和操作系统方面
- 说一下TCP的三次握手？
- 什么时候用多线程？多线程的优势是什么？为什么用多线程不用多进程？python的多线程start以后立马能起来吗？
- 讲一下IO多路复用？

##### flask方面
- Flask的底层原理讲一下？描述一下flask是怎么处理url请求的，整个底层流程是怎么样大概说下就行；
- endpoint是啥，讲一下？
- before request有用过吗？触发before request钩子是在view function以前还是以后？
- 常用的rest接口有哪些？你是怎么写类视图的？例子讲一下；
- 大概就这么多，其他问题的想不起来了

##### mysql方面
- 讲下聚簇索引？
- 聚簇索引的优点？
- 为什么使用B+树作为索引数据结构？
- 你是怎么sql或者索引调优的？慢查询日志里面的内容是啥？

数据库方面问的不多，比较简单，如果忘了可以看我右边这篇博客[Github-Mysql热点问题总结](https://github.com/ewenliu/Learning_Note/blob/master/Mysql%E7%83%AD%E7%82%B9%E9%97%AE%E9%A2%98%E6%80%BB%E7%BB%93.md)

##### redis方面
- redis常用的数据类型有哪些？
- 持久化rdb和aof讲一下
- 知道redis中list的底层实现原理吗？  

redis问也比较基础，如果忘了可以看右边这篇博客[Github-Redis热点问题总结](https://github.com/ewenliu/Learning_Note/blob/master/Redis%E7%83%AD%E7%82%B9%E9%97%AE%E9%A2%98%E6%80%BB%E7%BB%93.md)

##### python基础
- 用的是python2还是3？为什么用3？知道最新的稳定版本是哪个吗？
- 知道python3的新特性吗？
- 迭代器和生成器说一下？
- 类方法用过吗？__str__和__repr__区别？
- 类里面怎么实现__iter__？
- GIL讲一下？讲一下多线程下GIL和线程的关系？
- 协程用过吗？yield讲一下


#### 二面

- 未来有什么职业规划？
- 觉得杭州怎么样？
- 觉得技术该如何深入？哪方面深入有想过吗？
- 觉得python未来怎么样？python机会这么少有考虑以后怎么深入学习吗？
- 聊一下高并发下缓存和数据库双写一致问题？
- 你有什么要问我的吗

### 总结
整体面的还行吧，只是岗位与个人职业规划有所出入，所以就没有后面了。


