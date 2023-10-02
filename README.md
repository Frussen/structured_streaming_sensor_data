<h1 align="center">Structured Streaming of Sensor Data</h1>
</br>
<p align="center">This project consist in the creation of a pipeline for the flow of sensor data from an Arduino console to a Databricks Delta Table, where a Spark cluster can be used for real-time data processing and analysis.</p>

</br>

<img width="auto" alt="image" src="https://github.com/Frussen/structured_streaming_sensor_data/blob/main/files/Structured%20Streaming%20Ironhack%20Project.png">
</br>

### Arduino
Arduino is an open-source electronics platform that consists of both hardware and software components, designed for creating interactive and programmable electronic projects. Sensors used:
- DHT11: for temperature and humidity observations
- SR04: sonar sensor for high frequence measuring of the nearest object distance
- PIR: Passive Infra-Red sensor for movement detection
</br>

### EMQX & MQTTX
MQTT is a lightweight, publish-subscribe, machine to machine network protocol for message queuing service. It is designed for connections with remote locations that have devices with resource constraints or limited network bandwidth, such as in the Internet of Things.
EMQX is an open-source, distributed MQTT messaging broker that can support millions of concurrent MQTT connections.

In this project an EMQX Cloud service enabled the connection of the Arduino signals to the Kafka Server thanks to the Data Bridge to Kafka feature.
The connection could then be easily tested with the help of the MQTTX client toolbox for desktop.

<img width="auto" alt="image" src="https://github.com/Frussen/structured_streaming_sensor_data/blob/main/files/emqx_data_bridge.png">
</br>

### Kafka
Kafka is an open-source distributed event streaming platform that allows real-time data ingestion, processing, and distribution across applications and systems.


### AWS
Cloud computing platform that provides a wide range of scalable and flexible cloud services and infrastructure.


### Spark
Apache Spark is an open-source unified analytics engine for large-scale data processing. It provides an interface for programming clusters with implicit data parallelism and fault tolerance.


### Databricks
Databricks is a comprehensive, cloud-based (AWS) data analytics and machine learning platform that offers the scalability and automation needed to handle complex data workflows.
Databricks provides a collaborative workspace where data engineers, data scientists, and analysts can work together to explore data, build data pipelines, develop machine learning models, and gain insights from their data.

