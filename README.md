  # blog-api and application
  blog application and blog-api

  # Main technologies
  Java 11, SpringBoot REST, Swagger, React, Ant-design UI library
  
  # Build and Running
  Unzip the Archive.zip, find frontend and backend application folders blog and postdisplay-api.
  
  # Running Backend API
  From the postdisplay-api folder execute below commands
  
  mvn clean install
  cd target/
  java -jar postsdisplay-api-0.0.1-SNAPSHOT.jar
  
  # Running Frontend application
  From blog folder execute below commands
  
  npm install
  npm start
  
  # Application URLS
  
  http://localhost:3000/
  
  # Swagger
  http://localhost:8080/swagger-ui.html#/blog-api-controller
  
  # Development and Production level points.
  
  I have limited the number fetching posts to 20 with related comments , this is only form the performance point, but in actual production development we
  can use caching methods to improve these.
  
  I have not added any security or API gateways for this design, In a actual production design along with other related services this can be developed as a
  Microservice with all service discovery, failover strategies, cofig management and container deployments.
  
  I have added one Unit test to show the approach and how we can Mock the services.
  
  Sawagger is used to document the API
