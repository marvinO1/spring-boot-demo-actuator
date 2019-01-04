# spring-boot-demo-actuator
Shows the usage of prometheus based metrics in a spring boot application.

# Create Docker image
```
docker image build -t marvino1/spring-boot-demo-actuator .
```

# Running Docker image
```
docker container run -d --name spring-8080 -p 8080:8080 marvino1/spring-boot-demo-actuator
docker container run -d --name spring-8081 -p 8081:8080 marvino1/spring-boot-demo-actuator
```
# Access application
```
http://localhost:8080
```
To see the counter ...

```
http://localhost:8080/actuator/
```
To see all actuator endpoints. 

