# yet-another-kafka (YaK)
An end-to-end socket programming based project to simulate Apache Kafka in a small scale, as a part of University Elective (Big Data - UE20CS322). <br/>

The following features are implemented:  <br/>
1. Producers publishing data to specific topics <br/>
2. Brokers to facilitate the pub-sub model between producers and consumers <br/>
3. Consumers that can subscribe and unsubscribe to specific topics <br/>
4. Zookeeper to monitor the broker nodes, perform implicit leader election and restarting of failure broker nodes <br/>
5. Fault tolerance due to data partitioning and storage in multiple nodes <br/>

Project Team:
1. Anusha Naik
2. K S Ramalakshmi
3. Vinay Kumar
4. Mohnish Sai Choudhary

<h1> How to run? </h1>
<lr>

Run each of the producer, consumer, broker and zookeeper in separate terminals <br/>

`python3 producer.py`
`python3 consumer.py`
`python3 mini-zookeeper.py`
