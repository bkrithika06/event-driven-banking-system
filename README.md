# Event-Driven Banking System

A Spring Boot backend banking system built using Apache Kafka, REST APIs, and H2 database integration.

## Features

* Kafka-based asynchronous transaction processing
* User balance validation and updates
* Incentive microservice integration
* REST API for querying balances
* H2 database persistence using JPA/Hibernate
* Event-driven architecture with Spring Kafka

## Tech Stack

* Java 17
* Spring Boot
* Apache Kafka
* Maven
* H2 Database
* JPA/Hibernate
* REST APIs

## Architecture

Frontend/Producer → Kafka Topic → Midas Core Consumer → Database + Incentive API

## Endpoints

### GET /balance

Returns the balance for a given user.

Example:

```bash
GET /balance?userId=1
```

## Learning Outcomes

* Event-driven backend systems
* Kafka consumers/producers
* REST microservice communication
* Database persistence and entity relationships
* Enterprise backend architecture principles
