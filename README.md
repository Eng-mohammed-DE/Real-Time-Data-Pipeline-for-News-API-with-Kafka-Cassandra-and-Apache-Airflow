# Real-Time-Data-Pipeline-for-News-API-with-Kafka-Cassandra-and-Apache-Airflow
This project builds a real-time data pipeline that streams news data from the News API into Kafka, and then stores it in Cassandra for efficient and scalable storage. Apache Airflow is used for orchestration, managing the entire pipeline to ensure smooth, real-time data processing and up-to-date news delivery.

Real-Time Data Pipeline for News API with Kafka, Cassandra, and Apache Airflow
Project Overview

This project builds a distributed real-time data pipeline that streams news articles from the News API into Apache Kafka and stores them directly into Apache Cassandra. Apache Airflow orchestrates and automates the workflow.
Architecture

    News API → Fetch live news articles

    Apache Kafka → Stream news articles in real-time

    Apache Cassandra → Store real-time news data

    Apache Airflow → Orchestrate and schedule the entire pipeline

Key Components

    Kafka Producer: Fetches news data from the News API and publishes it to Kafka topics.

    Kafka Consumer: Consumes news data from Kafka and writes it to Cassandra.

    Cassandra Database: Stores news articles for scalable and fault-tolerant retrieval.

    Airflow DAGs: Automate and monitor the end-to-end workflow.

Technologies Used

    Apache Kafka

    Apache Cassandra

    Apache Airflow

    Python

    News API

    How It Works

    Producer fetches real-time news articles and sends them to Kafka topics.

    Consumer listens to Kafka topics and writes the data into Cassandra tables.

    Airflow DAG automates the fetching, streaming, and storage tasks.

Benefits

    Real-time ingestion and storage of news data

    Scalable and distributed architecture

    Automated pipeline with minimal manual intervention

Author

Eng. Mohammed | Data Engineer
