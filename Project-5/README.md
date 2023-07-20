 ## Project #5

https://github.com/jason-qs/Restaurant-reviewer

 Overview
 - This is a backend REST API that uses encryption to safely encrypt sensitive data. This backend API is able to create, read, update, and delete data from a database

 - The use of this project is to create a backend service that functions a lot like YELP. Users are able to see review of restuarants and write their own reviews

 - Some important features are the use of JWT tokens to authenticate users, the project creates and issues JWT token to give users access to the endpoints. The endpoints are protected by Role-Based Access Control (RBAC) to ony give users like admins access to endpoints that give more control, while not letting regular users access to them. Another important feature is the encryption implementation that hashes sensitive information such as password in the database

 ## Technologies
- Kotlin
- Quarkus
- JWT

**Dependencies:**
- quarkus-kotlin
- quarkus-arc
- quarkus-junit5
- rest-assured
- kotlin-stdlib-jdk8
- kotlin-extensions
- quarkus-hibernate-orm
- quarkus-jdbc-h2
- quarkus-hibernate-orm-panache-kotlin
- quarkus-reactive-pg-client
- quarkus-jdbc-postgresql
- quarkus-smallrye-jwt
- quarkus-resteasy-reactive-jsonb
- spring-security-crypto

## Competencies
### JF 3.1-3.8 : Apply the process of server-side development, including explaining algorithms, logic and data structures, can develop and maintain databases and codebases, and explain and implement APIs

- I demonstrated this job function in this specific project as well during my employment at American Express. I worked on multiple server-side projects where I worked with codebases of varying sizes as well as different databases. In these projects, I had to connect to different Rest APIs, make sure data was encrypted, and use the proper data structures and logic to safely handle all the data
- The result of my actions was a meaningful contribution to my team and company. I also gained experience working with large codebases, server-side logic, and how encryption works
- This competency is connected to this project because I built a Quarkus backend that implements encryption, is a RESTful API, server-side logic, and connects to a Database

### JF 4.1-4.8 : Manage and deploy applications and programs, conduct testing, and adhere to industry security standards

- I demonstrated this job function while working on multiple projects during my employment at American Express. I created numerous unit tests across different projects to ensure the code I wrote was functioning to its requirements. Also, creating a Jenkins pipeline to prepare a project for continuous integration and continuous deployment. The following steps were taken to ensure the codebase was properly maintained. Using Junit and Mockito to create Unit tests. Ensure code is built to the right standard. As well as identifying the correct test scenarios and testing those scenarios
- The result of my actions was ensuring codebases were maintained correctly, and all further developments had unit tests created to ensure code quality. And having more insight into how applications are tested and deployed
- This competency is connected to this project because I had properly encrypt sensitive information and store it into the database. As well create code that is easily readable and maintanable.