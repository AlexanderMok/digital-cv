# Projects

## Data Pre-processing Pipeline for Network Acceleration Service 
- Tech: Python, Multiprocess, Delegation Pattern
- Time: 2017.03-2018.08
- Desinged and built a real time log pre-processing data pipeline via python multiprocess and delegation pattern.
- Implemented functions of real time data collection, decompression, cleansing and transformation.

## Real Time Log Processing System for Network Acceleration Service
- Tech: Flume,Kafka,Spark,Hive,HDP,MySQL
- Time: 2017.03-2018.05
- Designed and built a real time log processing data pipeline by Flume, Kafka, Spark, Hive, HDFS, MySQL. Implemented functions of data collection, cleansing, analyzing, and visualization.
- Customized Flume to incorporate Avro schema to transform row data to typed data, filtering out abnormal data. 
- Wrote data processing task in Spark Structured Streaming and Hive to manipulate the collected data and compute quality metrics and traffic usage of network acceleration service.
- Average 6-7min latency for 5min granularity metrics calculation. Replaced the original commercial software to process the logs and thus reduced cost.
