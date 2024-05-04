# Real-Time-Data-Streamer

A dynamic real-time data streamer that integrates Apache Airflow, Kafka, Apache Spark, Cassandra, PostgreSQL, and Docker to provide a robust pipeline for processing and storing various data sources. Data ingestion is performed through Kafka, followed by Apache Airflow for scheduling Spark jobs to process, filter, and transform the raw data. The processed data is then stored in a Cassandra NoSQL database. Each component of the architecture has been containerized using Docker, ensuring streamlined deployment and management.
