# kafka
Reference for apache kafka


Apache kafka
Apache Kafka is an open-source stream-processing software platform 

Package sarama is a pure Go client library for dealing with Apache Kafka (versions 0.8 and later). It includes a high-level API for easily producing and consuming messages, and a low-level API for controlling bytes on the wire when the high-level API is insufficient.

General Terminologies
--------------------
Producer

Consumer

Consumer group 

sarama client
-------------
AsyncProducer
 Receives message in channel and writes to kafka in the back ground
SyncProducer
provides a method which will block until the kafka acknowledges the writes, 

Consumer
ConsumerGroup

Lower layer
----------
For the lower layer operations the sarama client provides the below objects 
Broker 
Request/Response 

