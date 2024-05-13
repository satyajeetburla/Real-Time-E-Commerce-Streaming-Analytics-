# Real-Time E-Commerce Streaming & Analytics 

## Project Overview
Implemented an end-to-end real-time streaming and analytics solution for e-commerce data using Apache Flink. The system ingests sales data through Kafka, processes it in Flink, and stores results in PostgreSQL for analytics and Kibana for visualization.

## Data Engineering Pipeline
![System Architecture.png](https://github.com/satyajeetburla/Real-Time-E-Commerce-Streaming-Analytics-/blob/main/System%20Architecture.png)

### Components

#### Apache Flink
- Configures the Flink execution environment.
- Integrates with Kafka to receive real-time financial transaction data.
- Processes, transforms, and aggregates transaction data streams.

#### PostgreSQL
- Maintains tables for storing transaction data and aggregated results (`transactions`, `sales_per_category`, `sales_per_day`, `sales_per_month`).

#### Elasticsearch
- Houses transaction data for advanced analysis and visualization.
