# apacheKafka

# Apache Kafka


## Introduction


In the current scenario, Big data uses large amount of data and mainly there are two challenges in big data.
1. How to collect large amount of data
2. Analyzing data

To overcome these challenges we need messaging system.Messaging System are those which is responsible for transferring the data from one application to another. So, that the application can only focus on data and don't worry how to share it.

***Apache Kafka is a distributed publish-subscribe messaging system and a robust queue that can handle a high volume of data and enables you to pass messages from one end-point to another.*** 

Kafka is suitable for both offline and online message. Its messages are persisted on the disk and replicated within the cluster to prevent data loss. It is built on top of the ZooKeeper synchronization service and it integrates very well with Apache Storm and Spark for real-time streaming data analysis.

## Benefits of Kafka

Kafka is very fast and guarantees zero downtime and zero data loss. Following are the some benefits of Kafka...

- Reliability
- Scalability
- Durability
- Performance

## Use Cases of Kafka

There are many uses cases of Kafka but some are listed below.

- Messaging System: Millions of messages can be sent and received in real time, using Kafka.

- Activity Tracking: Kafka can be used to aggregate user activity data such as clicks, navigation and searched from different websites of an organization and such user activities can be sent to a a real time monitoring system and hadoop system for offline processing.

- Metric: It can be used for aggregating statistics from distributted applications to produce centralized feeds of operational data.

- Log Aggregation Solution: Kafka can be used across an organization to collect logs from multiple services and make them available in a standard format to multiple consumers.

- Commit Log Service: Kafka can be used as an external commit log for distributed systems.

- Stream Processing: Many popular frameworks are available like storm, spark which can perform stram processing but Apache Kafka's strong durability is also very useful in the context of stream processing.

## Need of Kafka

- Kafka is a unified platform for handling all the real-time data feeds.
- It supports low latency message delivery and gives guarantee for fault tolerance in the presence of machine failures.
- It has the ability to handle a large number of diverse consumers.
- Kafka is very fast, can performs 2 million writes/sec. 
- Kafka persists all data to the disk, which essentially means that all the writes go to the page cache of the OS (RAM). This makes it very efficient to transfer data from page cache to a network socket.

## Kafka is able to solve following Poblems

- How data is transported with different protocols (TCP, HTTP, REST, FTP etc)

- How data is parsed for different data formats (Binary, CSV, JSON etc.)

- How data is shaped and may change. Decoupling of Data Streams & Systems

## Features of Kafka

- Distributed

- Resilient

- Fault Tolerant

- High performance (latency of less than 10 ms) – real time

- High Throughput

- Open Source


# References

<https://chouhans.wordpress.com/2019/05/15/my-learning-notes-on-apache-kafka/>

<https://en.wikipedia.org/wiki/Apache_Kafka>

<https://www.tutorialspoint.com/apache_kafka/apache_kafka_introduction.htm>







```python

```


```python

```
