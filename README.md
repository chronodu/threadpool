# threadpool
High performance thread pool
使用很简单：

1.ThreadPool pool 用threadpool这个类定义一个pool对象

2.pool.setMode() 设置模式 （fixed模式或者cached模式）

3.pool.start() 启动线程池 （把线程都创建起来 等待任务过来 执行任务）
