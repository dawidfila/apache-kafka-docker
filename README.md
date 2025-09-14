# Apache Kafka Docker Setup

This repository contains a ready-to-use Docker Compose setup for running Apache Kafka locally. It is ideal for learning, experimenting, or following along with tutorials.

## Requirements

- Docker
- Docker Compose

## Getting Started

1. **Clone this repository**  
```bash
git clone https://github.com/dawidfila/apache-kafka-docker.git
cd kafka-docker-tutorial
```

2. **Start Kafka**  
```bash
docker-compose up -d
```
This will start Kafka and its necessary components.

3. **Verify Kafka is running**  
```bash
docker ps
```
You should see the Kafka container running.

## Stopping Kafka

To stop Kafka, run:  
```bash
docker-compose down
```

## Notes

- The Kafka data is persisted in the `./kafka_data` folder.
- You can customize ports and configuration in `docker-compose.yml`.
