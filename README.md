# Java Spring Tutorial
Building a RESTful Web Service

## Build and Run
```bash
# Build JAR file using gradle wrapper
./gradlew build

# Run the JAR file
java -jar build/libs/gs-rest-service-0.1.0.jar
```

## Testing the Service
Service runs locally on port 8080: [http://localhost:8080/greeting](http://localhost:8080/greeting)

The query parameter `name` can be used to customize reponse: [http://localhost:8080/greeting?name=User](http://localhost:8080/greeting?name=User)

```json
{
    id: 1,
    content: "Hello, User!"
}
```