
1. 广播onReceive之后, 如果没有其他组件在运行, 直接采用线程的方式是不可靠的, 可能被杀.
建议创建JobService.
