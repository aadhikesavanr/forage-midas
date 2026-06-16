# Midas
Project repo for the JPMC Advanced Software Engineering Forage program

#JPMorgan Midas Core


#Overview

This project was completed as part of the JPMorgan Chase Software Engineering Virtual Experience Program.

The application processes financial transactions using Kafka, validates them against user account balances, stores them in an H2 database, integrates with an external Incentive API, and exposes REST endpoints for querying balances.

#Features
Kafka Transaction Consumer
Transaction Validation
H2 Database Integration
Spring Data JPA
Incentive API Integration
User Balance Management
REST API for Balance Queries


#Technologies Used
Java 17
Spring Boot
Apache Kafka
H2 Database
Spring Data JPA
REST APIs
Maven


#Tasks Implemented

Task 1

Configured and explored the project structure.

Task 2

Implemented a Kafka consumer to receive transaction messages.

Task 3

Added transaction validation and database persistence.

Task 4

Integrated the external Incentive API and updated balance calculations.

Task 5

Developed a REST API endpoint to query user balances.

#API Example
Get Balance
GET /balance?userId=5

#Response:

{
  "amount": 444.55
}


#What I Learned
Event-driven architecture using Kafka
Database design with JPA entities
REST API development with Spring Boot
External API integration using RestTemplate
Transaction validation and persistence


#Repository Structure
src/
 ├── component/
 ├── controller/
 ├── entity/
 ├── foundation/
 ├── repository/
 └── resources/
