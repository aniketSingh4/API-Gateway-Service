This project demonstrates a microservices architecture using an API Gateway that routes requests to two backend services:
1. Product Service
2. Customer Service

The **API Gateway** handles incoming HTTP requests and forwards them to the appropriate microservice based on the URL path. It simplifies the client-side architecture by:

- Centralizing routing logic
- Providing a unified API interface
- Enabling load balancing, rate limiting, and security.
