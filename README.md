# Spring Boot Angular 2 Starter
Inspired by [borsyn's](https://github.com/borysn/spring-boot-angular2) but with maven instead of gradle
Heavily influenced by [this jDriven article](https://blog.jdriven.com/2016/12/angular2-spring-boot-getting-started/)

## Contents
[Prerequisites](#prerequisites)

[Running](#running)

### Prerequisites
| Prerequisite                                  | Version |
| --------------------------------------------- | ------- |
| [JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk9-downloads-3848520.html) | `~ ^1.8.x` |
| [Maven](http://maven.apache.org/download.cgi) | `~ ^3.1.x` |
| [Node.js](http://nodejs.org)                 | `~ ^6.9.x`  |
| npm                                          | `~ ^3.x.x`  |
| @angular/cli                                 | `latest` |

### Running
1. Run `mvn clean install` in the top level directory to build the project
2. `cd backend`
3. Run `mvn spring-boot:run` in the backend directory to run the application
4. The project should be accessible at `localhost:8080`

**Note:** Spring Boot recommends exporting the following when running from the command line: `export MAVEN_OPTS=-Xmx1024m -XX:MaxPermSize=128M`