# KafkaAssignment

Produce a user message into a Kafka topic and consume it using the Kafka Producer and Consumer APIs. Once the message is consumed from a consumer, it should be sinked(written) into a file.
Message Structure
User message --->{"id":"1","name":"some_name","age":"24","course":"BTech."}

-Create Producer API class for publish the message on Broker
-Create Consumer API class for consume the message from Broker
-Create StudentInformation class
-Create Serailization and Deserialization class for converting the message in byte stream form when it is send from Producer and again deserialize the message when it is consumed by Consumer
