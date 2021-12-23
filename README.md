关联维表的三种基础方式：

- 实时数据库查询关联 [ 流批关联 ]
    - 同步数据库查询关联
    - 异步数据库查询关联
    - 带缓存的数据库查询关联
- 预加载维表关联 [ 流批关联 ]
    - 启动时预加载维表(每个并行全量加载)
    - 启动时预加载分区维表(每个并行各加载部分)
- 维表变更日志关联 [ 流流关联 ]


## 参考

1. Flink 中文社区：https://flink-learning.org.cn/article/detail/b8df32fbc6542257a5b449114e137cc3?spm=a2csy.flink.0.0.49493bdcLZAWkq
