
## Why use spring boot
* First of all, it makes use java, Spring boot isamazing that helps you to get enterprise-grade applications up and running quickly without having to worry about configuring your application correctly and safely.
some additional benefites 
* Reduces development time and increases the overall productivity of the development team. 
* Helps you autoconfigure all components for a production-grade Spring application.
* Makes it easier for developers to create and test Java-based applications by providing a default setup for unit and integration tests. 
* Avoids writing lots of boilerplate code, annotations, and XML configuration. 
* Comes with embedded HTTP servers like Tomcat or Jetty to test web applications. 
* Adds many plugins that developers can use to work with embedded and in-memory databases easily. Spring allows you to easily connect with database and queue services like Oracle, PostgreSQL, MySQL, 

## Installation backend
 * Go inside of project and run ./mvnw spring-boot:run
 * The project is host in http://localhost:8090/api/beers
 * If you have to test api, you can do that on http://localhost:8090/swagger-ui.html

## Installation frontend(Optional)
 * Download node version and install global
 * Now just go in frontend folder and just write npm i after that npm run serve  you can see project with CRUD 
   on frontend
   * ![beer](https://user-images.githubusercontent.com/72534020/130164518-462aa7e1-491d-4919-953e-33d9dbe79567.png)


## What i can do better
* Better handle exception, better write README file for sure and clear code writing, with maybe a few extra methods for something repetitive,
  make a method for save() and saveAll(), for POST request, In case I receive an xml file from several beers I would use saveAll(), and when I receive only one beer save().
.
* Better handle exception, better write README file for sure and clear code writing, with maybe a few extra methods for something repetitive.

