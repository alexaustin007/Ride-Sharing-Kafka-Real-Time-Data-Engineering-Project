# Ride-Sharing-Kafka-Real-Time-Data-Engineering-Project
I have used different technologies such as Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena and SQL.


In this project I created a AWS EC2 instance installed Kafka on that and java(since kafka runs on top of JVM).

Started Zookeeper in one terminal
Started Kafka in another terminal

Started producer in another
Created a topic in that terminal so as to send data in that particular topic.

Started Consumer to to consume/read the date in real time.

Wrote the producer data in S3

Read those S3 data via glue crawler.

Analysed and got the final output in Athena.


Architecture Flow .

![Architecture_ride_sharing](https://user-images.githubusercontent.com/75135556/208143418-c941da24-96c2-4214-b180-ff8f44bd3eba.jpg)




