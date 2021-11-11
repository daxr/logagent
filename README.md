# logagent
1.使用 "github.com/go-ini/ini" 提供文件读取配置  
2.通过etcd进行日志收集项配置文件管理  
3.使用kafka实现发布订阅模式，作为日志的“通道”  
4.tailf模块负责读取所在节点对应的log文件，使用sarama发送至kafka  
