# SpringBoot

## Remark:
This practice is following [this](https://spring.io/guides/gs/rest-service/) website.
- 1.Create build.gradle file

- 2.Create a resource representation class 
	- java object(Greeting.java)

- 3.Create a resource controller
	- GreetingController.java
	- @RestController
	- @RequestMapping("/greeting")

- 4.Make the application executable
	- Application.java
	- @SpringBootApplication

- 5.Build an executable JAR
	- Run Command ```./gradlew build``` to build the JAR file
	- ```java -jar target/gs-rest-service-0.1.0.jar``` to run the application locally

- 6.Test the Application locally
	- Go to [local address](http://localhost:8080/greeting)  http://localhost:8080/greeting
	- Or [Provide a name query string parameter](http://localhost:8080/greeting?name=User) with http://localhost:8080/greeting?name=User. 