## springboot-postgres-demo
A simple demo of Spring boot, Postgresql, JPA, and Hibernate REST API.
Dockerfile is added for dockerized purpose.

## Credit:
A copied of the original project at [Spring Boot, PostgreSQL, JPA, Hibernate RESTful CRUD API Example](https://www.callicoder.com/spring-boot-jpa-hibernate-postgresql-restful-crud-api-example/) and [source code](https://github.com/callicoder/spring-boot-postgresql-jpa-hibernate-rest-api-demo)

## Steps to Setup

**1. Clone the repository**

```bash
git clone https://github.com/VanLePham/springboot-postgres-demo.git
```

**2. Configure PostgreSQL**

First, create a database named `postgresdemo`. Then, open `src/main/resources/application.properties` file and change the spring datasource username and password as per your PostgreSQL installation.

**3. Run the app**

Type the following command from the root directory of the project to run it -

```bash
mvn spring-boot:run
```

Alternatively, you can package the application in the form of a JAR file and then run it like so -

```bash
mvn clean package
java -jar target/postgres-demo-0.0.1-SNAPSHOT.jar
```
