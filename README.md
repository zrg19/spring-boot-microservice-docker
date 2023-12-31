

# Microservices Architecture with Spring Boot and Docker

Welcome to the Microservices Architecture application! This project showcases a robust system built using Spring Boot 3, Spring Cloud, Docker, and various databases for microservices communication.

![img.png](img.png)

## Prerequisites

Before you begin, ensure you have the following installed:

- [JavaJDK 17](https://openjdk.org/projects/jdk/17)
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Getting Started

Follow these steps to get the Microservices Architecture up and running:

1. Clone the repository:

   ```bash
   git clone https://github.com/zrg19/spring-boot-microservice-docker.git
   ```

2. Navigate to the project directory:

   ```bash
   cd spring-boot-microservice-docker
   ```

3. Build the Docker images:

   ```bash
   docker-compose build
   ```

4. Start the services:

   ```bash
   docker-compose up -d
   ```

   The `-d` flag runs the services in the background.

5. Monitor the logs:

   ```bash
   docker-compose logs -f
   ```

   Use `Ctrl + C` to exit the log monitoring.

## Accessing Services

Once the services are up and running, you can access the following services:

- **Eureka Discovery Server:**
    - http://localhost:8761

- **API Gateway:**
    - http://localhost:8181

- **Zipkin Tracing:**
    - http://localhost:9411

Adjust the ports accordingly if you have conflicting services running on your machine.

## Stopping the Services

To stop the services and remove the containers, run:

```bash
docker-compose down
```

## Contributing

Feel free to contribute and enhance this Microservices Architecture. Submit pull requests, report issues, or share your feedback.

Happy coding! 🚀
