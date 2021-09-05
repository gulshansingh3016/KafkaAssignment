# KafkaAssignment

Produce a user message into a Kafka topic and consume it using the Kafka Producer and Consumer APIs. Once the message is consumed from a consumer, it should be sinked(written) into a file.
Message Structure
User message --->{"id":"1","name":"some_name","age":"24","course":"BTech."}

1. Create Producer API class for publish the message on Broker
2. Create Consumer API class for consume the message from Broker
3. Create StudentInformation class
4. Create Serailization and Deserialization class for converting the message in byte stream form when it is send from Producer and again deserialize the message when it is consumed by Consumer

* START THE KAFKA ENVIRONMENT

> $ bin/zookeeper-server-start.sh config/zookeeper.properties

* START THE KAFKA SERVER

> $ bin/kafka-server-start.sh config/server.properties

*Create Topic

> $ bin/kafka-topics.sh --create --topic student-info --bootstrap-server localhost:9092

