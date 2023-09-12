# Webserver

项目描述：

使用线程池 + 非阻塞socket + select/poll/epoll + 事件处理(Reactor和多reactor均实现) 的并发模型
使用CMake实现项目的快速部署
使用状态机解析HTTP请求报文，支持解析GET和POST请求，实现请求图片和视频文件等静态资源
经Webbench压力测试可以实现上万的并发连接数据交换



