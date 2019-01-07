# KafkaSimpleExample

## 代码说明
https://www.imooc.com/learn/1043
启动zookeeper 启动kafka 
F:\kafka_2.11-1.0.0\bin\windows>kafka-server-start.bat ../../config/server.properties
创建kafka topic
F:\kafka_2.11-1.0.0\bin\windows>kafka-topics.bat --create --zookeeper localhost:2181 --replication-factor 1 --partitions 3 --topic imooc-kafka
