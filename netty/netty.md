# netty架构
![netty架构图](https://netty.io/images/components.png)
# netty主要模块 
* buffer
* codec
    - http
    - http2 
    - redis
* `transport`
    - EvenLoop
    - Channel
        * Channel是nio中的一个概念,channel上可以进行数据的输入和输出。
        * Channel操作的对象是buffer
    - Selector
        * epoll
    - Handler

