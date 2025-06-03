# E-Commerce Platform Monolith

This repository contains the legacy monolithic e-commerce platform that is being modernized as part of the E-Commerce Platform Modernization project.

## Project Overview

This platform is being decomposed into microservices as documented in [E-Commerce Platform Overview](../confluence_samples/01_ecommerce_platform_overview.html).

## Related Jira Stories
- [ECOM-1001](../jira_stories/ECOM-1001.json): Implement product recommendation engine for e-commerce platform
- [ECOM-1002](../jira_stories/ECOM-1002.json): Implement recommendation service client

## Architecture

The current monolithic architecture includes:

- Product catalog management
- Shopping cart functionality
- Checkout and payment processing
- User account management
- Order management
- Inventory management
- Search functionality
- Basic recommendation engine

## Technology Stack

- Java 8
- Spring Framework 4.3
- Hibernate ORM
- MySQL Database
- Apache Tomcat
- JSP/JSTL
- jQuery
- Bootstrap CSS

## Getting Started

### Prerequisites
- JDK 8
- Maven 3.6+
- MySQL 5.7

### Build and Run
```bash
mvn clean install
mvn spring-boot:run
```

## Modernization Plan

This monolith is being decomposed into microservices as part of the E-Commerce Platform Modernization project. The new architecture will be deployed on AWS using containerization and will follow a domain-driven design approach.

See the [Microservices Decomposition Plan](../confluence_samples/01_ecommerce_platform_overview.html) for details on the modernization strategy.
