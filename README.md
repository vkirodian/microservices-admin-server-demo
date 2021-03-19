# microservices-admin-server-demo

This is a simple Spring Boot Cloud Administrator Server.

## Installation

Once you have checked out this repository, go to the base directory and build it using maven

```bash
maven clean install
```

## Running the application

Once the project is successfully built, you can run the following command:

```bash
java -jar .\target\microservices-admin-server-demo-1.jar
```

The application would run at the configured port and act as a administrator server for all your micro-services.

Currently the application.properties is configured to run at http://localhost:9090.

It will pick up all the applications registering using spring.boot.admin.client.url property.

Also the client need to have actuator enabled.

Download and use https://github.com/vkirodian/spring-boot-example which has Cloud Administrator Client enabled.