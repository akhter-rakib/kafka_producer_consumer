# kafka_producer_consumer
# To start the Zookeeper run the following command
-- bin/zookeeper-server-start.sh config/zookeeper.properties
# To start the Kafka run the following command
-- bin/kafka-server-start.sh config/server.properties
# Console of Kafka consumer
-- bin/kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic myTopic