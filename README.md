# Webserver

项目描述：

使用线程池 + 非阻塞socket + select/poll/epoll + 事件处理(Reactor和多reactor均实现) 的并发模型
使用状态机解析HTTP请求报文，支持解析GET和POST请求，实现请求图片和视频文件等静态资源
 经Webbench压力测试可以实现上万的并发连接数据交换

个人总结：

学习生产者消费者模型，掌握线程同步的基本手段，如互斥锁、条件变量等；
对HTTP的服务过程有了更清晰的认识，将Linux下的socket多线程编程以及I/O多路复用知识运用到了实际项目中
