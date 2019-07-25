# java-springboot-vscode-setup
Repository to represent how to create a springboot project on VS Code

# Setup to run on VS Code

## Install:

* Spring Initializr Java Support
* Java Extension Pack (Needs JDK 11)
* Spring Boot Dashboard
* Debugger for Java

## Steps:

* 1 - CTRL + P > Spring
* 2 - Spring Initializer: Generate a Maven Project > Java
* 3 - Put the GourpId and ArtificatId for your project
* 4 - Select Spring Boot version
* 5 -  Add dependencies: Web, DevTools, Actuator Ops
* 6 - Change server port: 
* * Go to src > main > resources > application.properties > server.port=9898
* 7 - Run app
* 8 - Install lombok extension
* 9 - Add swagger dependencies and SwaggerConfig.java file

## PS:

Install dotnet core could be useful

## Links:

* http://localhost:9898/swagger-ui.html#/

* https://start.spring.io/

* https://www.baeldung.com/swagger-2-documentation-for-spring-rest-api
