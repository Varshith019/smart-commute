
# SmartCommute

SmartCommute is a ride-sharing backend platform designed to connect
commuters traveling along similar routes.

## Status
🚧 In Development

## Tech Stack
- Java
- Spring Boot
- PostgreSQL
- Redis
- REST APIs
- Maven

## Planned Features
- User registration and authentication
- Create and manage rides
- Search available rides
- Route-based ride matching
- Seat booking
- Concurrent booking protection
- Redis caching
- REST API architecture

## Planned Architecture

Client
  |
  v
Spring Boot REST API
  |
  +--- Controller
  |
  +--- Service
  |
  +--- Repository
        |
        +--- PostgreSQL
        |
        +--- Redis
