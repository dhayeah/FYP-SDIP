FYP-SDIP: Stream Data Ingestion and Processing
Overview
Welcome to the FYP-SDIP repository, a Final Year Project focused on Stream Data Ingestion and Processing (SDIP). This project demonstrates the design and implementation of real-time data pipelines for efficient ingestion, processing, and analysis of streaming data. Built with scalable technologies, it aims to optimize throughput and ensure data integrity for high-velocity data streams.

The project leverages Apache Kafka for stream ingestion and Apache Spark for processing, with additional tools for data pipeline orchestration and monitoring. It serves as a proof-of-concept for real-time data workflows, applicable to use cases such as IoT, financial transactions, or log analytics.

Features
Real-Time Data Ingestion: Seamlessly ingests high-velocity data streams using Apache Kafka.
Scalable Processing: Processes streaming data with Apache Spark, enabling complex transformations and analytics.
Optimized Throughput: Ensures low-latency and high-throughput data pipelines.
Data Integrity: Implements robust mechanisms to maintain data consistency and reliability.
Extensible Architecture: Modular design for easy integration with additional data sources or processing logic.
Technologies Used
Apache Kafka: For distributed streaming and message brokering.
Apache Spark: For stream processing and data analytics.
Scala: Primary programming language for implementing processing logic.
Python: For scripting and auxiliary tools.

Prerequisites
To run this project locally, ensure you have the following installed:

Java JDK 8 or higher
Scala 2.12.x
Apache Kafka 2.8.x
Apache Spark 3.2.x
Python 3.8+
Maven 3.6.x
Installation
Clone the Repository:
bash

Copy
git clone https://github.com/dhayeah/FYP-SDIP.git
cd FYP-SDIP
Set Up Kafka and Zookeeper:

Start the Kafka Producer:
Run the producer script to simulate streaming data:
bash

Copy
python scripts/producer.py
Run the Spark Application:
Submit the Spark job to process the streaming data:
bash

Copy
spark-submit --class com.dhayeah.fyp.StreamProcessor target/fyp-sdip-1.0.jar
