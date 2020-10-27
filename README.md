# Service Registration and Discovery examples with Spring Boot
This git repository contains 3 Eclipse projects, one application for server side named 'service-discovery-server' and two applications for client side, first is student services application named 'service-discovery-client1' and another one is teacher services application named 'service-discovery-client2' which used RESTful services from the first application.

## Setup
1. Build and run App.java in *'service-discovery-server'*
2. Build and run App.java in *'service-discovery-client1'*
3. Build and run App.java in *'service-discovery-client2'*
4. Check student services by calling **HTTP GET** [http://localhost:8081/v1/student/61070003](http://localhost:8081/v1/student/61070003)
5. Get result from teacher service which pass request through student service by calling **HTTP GET** [http://localhost:8082/v1/teacher/studentReport](http://localhost:8082/v1/teacher/studentReport)

## Dashboard
http://localhost:8761/index
![Screenshot_2020-10-27 Screenshot](https://user-images.githubusercontent.com/43009070/97308613-a4424e00-1893-11eb-8b10-70149e9458e9.png)
