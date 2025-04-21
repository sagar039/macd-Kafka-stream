# macd-Kafka-stream
# McDonald's Real-Time Order Processing and Visualization Pipeline

## Overview
This project implements a **real-time order processing pipeline** for McDonald's, leveraging **Apache Kafka, Avro, Confluent Schema Registry, Python, and MongoDB**. The system ingests, processes, and visualizes order and payment data in real time, ensuring efficient transaction handling and business insights.

## Architecture
1. **Data Generation**:
   - Simulated real-time McDonald's order and payment events using Python's `random` and `uuid` libraries.
2. **Data Ingestion**:
   - Published order (`macd_orders`) and payment (`macd_payments`) events to Kafka topics.
   - Used **Avro serialization** for efficient message encoding and schema management.
3. **Data Processing**:
   - Consumed Kafka events and processed them for real-time analytics.
4. **Storage & Visualization**:
   - Stored processed data in **MongoDB**.
   - Used MongoDB's inbuilt visualization tools to generate insights into order trends and payment behaviors.

## Tech Stack
- **Streaming Platform**: Apache Kafka
- **Schema Management**: Avro, Confluent Schema Registry
- **Programming Language**: Python
- **Database**: MongoDB
- **Data Processing**: Kafka Consumer (Python)

## Features
- Real-time order and payment processing using Kafka.
- Avro serialization for optimized message storage.
- MongoDB integration for persistence and analysis.
- Fault-tolerant and scalable pipeline design.
- Real-time analytics for business insights.

## Future Enhancements
- Implement **real-time dashboards** using **Grafana**.
- Integrate **Apache Spark Streaming** for advanced analytics.
- Deploy on **Google Cloud Platform (GCP)** with **Dataproc & BigQuery**.

## Contributing
Feel free to fork this repository and open a PR for any improvements!
