
# AtmosIQ 🌍

atmosIQ is a real-time data engineering platform that ingests air quality data and serves analytics-ready datasets for monitoring and insights.

## Problem Statement
Air quality data is generated continuously by sensors across different locations. This data is often noisy, arrives late, and evolves over time. Reliable ingestion and processing of this data is critical for public health analysis and regulatory reporting.

AtmosIQ focuses on building a robust Spark-based pipeline that handles these challenges while remaining observable, replayable, and scalable.

## Project Goals
- Process historical and streaming air quality data using Apache Spark
- Model data using analytical storage formats
- Handle schema evolution and late-arriving data
- Demonstrate production-style design decisions

## Tech Stack (initial)
- Apache Spark (PySpark)
- Python
- Parquet (initial storage format)

Later phases will introduce:
- Kafka
- Spark Structured Streaming
- Iceberg

## Repository Structure (WIP)
