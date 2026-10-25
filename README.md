# Maven_project
It is just the simple project I build to understand how the projects structure and how everything works
I learnt how to create a project using maven and below is the flow
1. Go to chrome and search for Spring initializr
2. choose maven as a project, java as a language, select a stable version of spring boot, also fill the project metadata such as group which is domain name
   Artifact, Name, Desc, and add package name
3. also add dependencies such as (i) spring web, (ii) spring boot devtools
4. Maven automatically downloads the required deps, intellij makes them available to ur java code, and spring boot uses those liberaries to start our application

   AFTER THE PROJECT IS CREATED OPEN IT IN ANY ide AND OPEN pom.xml FILE
1. Add the required dependencies inside the dependencies tag
2. create a package structure, which includes, entity, controller, repository, and services
3. All of these packages defined in step 2 should be inside the main package and all should contain some java files depending upon the complexity of the project
4. entity - In this package all the database schemas will be written
5. controller - Here the HTTP methods are defined such as Get, Put, Post, Delete, etc
6. repository - This is the layer that accesses Database, Spring Data JPA generates the implementations for us, so we don't need to write SQL for basic CRUD operations
7. services - This is where the functions which are needed for the controller to process the data are written
8. src/main/resources/application.properties - This is the location where database connections and the port where the backend can be made available is written it act as .env file in MERN Stack

    FRONTEND
React can be used for frontend along with tailwind.css
