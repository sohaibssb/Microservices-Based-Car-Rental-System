# Microservices-Based Car Rental System

Programmed by Sohaibssb for "Distributed information processing systems" Course-Master degree at Bauman University.

This repository houses a car rental system project built with a microservices architecture, employing modern tools and frameworks to achieve modularity, scalability, and efficient communication between services.

Technologies Used in the Car Rental System Project:

Python & Flask: Backend services implemented using Python and the Flask web framework.
React & CSS: Frontend built with React for dynamic UI, styled with CSS.
Kafka: Event streaming used for real-time data processing between services.
OpenID Connect: Ensures secure authentication and authorization of users.
Docker & Kubernetes: Services isolated in Docker containers and managed with Kubernetes.
GitHub Actions: CI/CD pipeline for automated testing and deployment.

Features:

1- Microservices Architecture:
The system comprises various services, each handling a specific domain: Car, Rental, Payment, Gateway, Identity Provider, and Statistics.
Each service has its own storage and handles all requests via HTTP RESTful APIs.

2- Gateway Service:
Serves as the central entry point, routing incoming user requests to the relevant services.
Aggregates data from multiple microservices to deliver a unified response.

3- Key Services & Components:
- Car Service: Manages vehicle information and inventory.
- Rental Service: Handles booking, customer information, and rental contracts.
- Payment Service: Processes payments securely, integrating with external payment gateways.
- Identity Provider Service: Provides authentication and authorization, using OpenID Connect.
- Statistics Service: Gathers data on transactions and user activity, and sends it to Kafka for analysis.
  
4- Deployment & Infrastructure:
Utilizes Docker containers for service isolation and scalability.
Deployed with Docker Compose to simplify the setup and testing.
Github Actions for continuous integration with health check endpoints and automated unit testing.

5- Frontend:
A React-based user interface provides seamless interaction with the backend services.
Styled with modern CSS to ensure a consistent user experience.
