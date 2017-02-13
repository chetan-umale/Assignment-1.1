Q1. Various sources of Big Data
answer:
1.Sensor data
2.Archives
3.Documents
4.Social media
5.Buisness Apps
6.Public web
7.Machine Log Data
8.Personal storage devices like usb flash drives,portable hard disk


Q2. 3 V's of Big Data
answer:
1.Volume: The size of the data
2.Velocity: The rate of generation of data.
3.Variety: The different types of data.


Q3. Horizontal Scaling and vertical scaling.
answer:

Horizantal Scaling:
1.Horizontal scaling means that you scale by adding more machines into your pool of resources.
2.In a database world horizontal-scaling is often based on partitioning of the data i.e. each node contains only part of the data.
3.With horizontal-scaling it is often easier to scale dynamically by adding more machines into the existing pool.
4.Eg:Cassandra ,MongoDB

Vertical Scaling: 
1.Vertical scaling means that you scale by adding more power (CPU, RAM) to an existing machine.
2.In vertical-scaling the data resides on a single node and scaling is done through multi-core i.e. spreading the load between the CPU and RAM resources of that machine.
3.Vertical-scaling is often limited to the capacity of a single machine, scaling beyond that capacity often involves downtime and comes with an upper limit.
4.Eg:MYSQL


Q4. Need and Working of Hadoop.

answer:

Need of Hadoop:
1.With the advent of Big data, the limitations of existing systems in terms of storage and processing are well known.
2.As the data has become more heterogeneous,traditional rdbms systems are incapable of handing such data.
3.Hadoop provides a framework to tackle these challenges by using cheap commodity hardware and a simple programming model called mapreduce.
4.Hadoop has made it possible to store and process large volumes of data in a cheap and efficient manner as compared to proprietary solutions provided by companies like IBM.
5.This in turn has helped companies in deriving unique insights and make important strategic decisions in order to maximize profits.

Working of Hadoop:
1.Hadoop is a framework developed in java for handling big data.
2.It uses HDFS (Hadoop Distributed File System) for storage.
3.Hadoop uses a programming model called MapReduce for automated distributed computing.
4.There are various other components like Hive,Hbase,Pig etc.
