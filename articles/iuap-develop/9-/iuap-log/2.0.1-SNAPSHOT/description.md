﻿iUAP后台日志中，统一使用slf4j+logback的方式进行日志的记录和输出，通过slf4j对各个日志组件的桥接器，适配不同日志件对日志的输出。

同时，日志组件采用slf4j和MDC的结合，可以在日志中记录如用户编号，线程调用唯一标识等指定信息，方便问题的追踪，为运维管理中如ELK方案追踪日志信息提供线索。