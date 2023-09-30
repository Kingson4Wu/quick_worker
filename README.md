# quick_worker

1. 基于channel生产者消费者模式异步操作数据
2. 使用Cond避免CPU空转的情况
3. 基于消费情况动态调整goroutine的数量
