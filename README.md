# Stock Market Data Processing Engine usking Kafka

## Introduction
This is an End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka.

We are going to use different technologies such as Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL.

## Architecture
![Kafka Architecture](https://user-images.githubusercontent.com/98258627/215194263-044c3f1c-52c7-4c82-8298-ab84a30984cb.jpg)


## Technologies Used
- Programming Language - Python
- Amazon Web Service (AWS)
- S3 (Simple Storage Service)
- Athena
- Glue Crawler
- Glue Catalog
- EC2
- Apache Kafka

## Kafka Setup

- You can either follow the `command.txt` to setup **kafka** on your EC2 instance or use `docker-compose` for easy setup
- Run the following command to setup kafka using `docker-compose`
```
docker-compose -f ./zk-single-kafka-single.yml up 
```
