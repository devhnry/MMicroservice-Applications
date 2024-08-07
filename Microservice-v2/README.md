# Banking System Microservices V2

## Overview

This project demonstrates how to separate a banking system into three distinct microservices: Loan, Account, and Card. The primary focus is on dockerizing the services, and creating a config server to manage properties for default, prod or qa in order to learn and understand property files in a microservices architecture. Followed by a Course I was taking.

## Microservices

1. **Loan Service**
2. **Account Service**
3. **Card Service**
4. **Config Server**

## Prerequisites

- Java Development Kit (JDK) 21.
- Docker
- Maven or Gradle (for building the project) **Maven was used.**

## Project Structure Summary

```
Microservice Application v2
├── accounts/
├── cards/
├── config-server/
├── docker-compose/
├── loans/
├── README.md
```

## Service: Dockerization

### Dockerfile

The Docker Compose file for the services is located in the `docker-compose` directory.

## Property Files

The `application.yml` files for the Account service is located in the `accounts` directory. It contains configuration settings for the service.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any changes.

---