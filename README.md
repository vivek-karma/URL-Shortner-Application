# Url-Shortner-Application

This Repository Contains Frontend and Backend code for Url-Shortner-Application.

Frontend Application is build using React technology \
Backend Application is build using Spring technology

### `Requirements to run Frontend Application` :
  - Node (v16.3.0 used)
  - npm (v6.14.7 used)
  - Visual Code IDE


### `Requirements to run Backend Application` :
  - Java 8
  - Maven
  - Eclipse IDE

In Memory Database is used in Backend Application for storing data. \
Data remains in the database until Backend Application is not closed.

## Backend Application Setup
1. Open Eclipse
2. Import Backend Project into eclipse workspace ( file -> import -> Existing maven project )
3. Browse folder Url-Shortner-Application/Backend
4. Eclipse will start setting up this Spring Boot Application by downloading required dependencies using maven
5. Once Setup is ready, Go to UrlshortnerApplication.java file in src/main/java/com/vivek/urlshortner package
6. Right click on main method and select Run as Java Application
7. Backend application will start on default embedded tomcat server at port 8080

## Frontend Application Setup
1. Open Visual code
2. Open Url-Shortner-Application/Frontend Folder in Visual code
3. Open cmd in Visual code (or open system cmd in the Url-Shortner-Application/ Frontend Folder)
4. Run command - npm install
5. The above code will install all the required dependencies required for the React application
6. Run command - npm start
7. The above code will run the Application on port 3000
8. Access the Application using http://localhost:3000 in Chrome Browser

Technologies used - Spring Boot, Spring REST, Spring JPA, H2 database, React, Redux, Bootstrap

Thanks \
Vivek Vishwakarma
