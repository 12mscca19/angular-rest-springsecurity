angular-rest-springsecurity
===========================

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=shoxrocks&url=https://github.com/philipsorst/angular-rest-springsecurity&title=Angular JS Spring Security Example&language=&tags=github&category=software) 

An example AngularJS Application that uses a Spring Security protected Jersey REST backend based on Hibernate/JPA.

About
-----

The projects aim is to demonstrate the Java implementation of a simple REST interface which is used by an AngularJS application. The following topics are covered:

* A relational database that holds news entries and users.
* A REST service that exposes the data in the database.
* Authentication and authorization against the REST service.
* A Simple AngularJS application that allows users to view or edit news entries depending on their role.
* A responsive design.
 
This project is just meant to be a demonstration, therefore it is neither well documented nor well tested. Use it to learn about the technologies used, but do not use it for productive applications.

Any feedback is welcome, and I will incorporate useful pull requests.

Technologies
------------

* [AngularJS](http://angularjs.org/)
* [Bootstrap](http://getbootstrap.com/)
* [Jersey](https://jersey.java.net/)
* [Spring Security](http://projects.spring.io/spring-security/)
* [Hibernate](http://hibernate.org/)

Running
-------

Make sure [Maven](http://maven.apache.org/) >= 2.2.1 is installed on your system. Go into the project dir and type `mvn jetty:run`, then point your browser to `http://localhost:8080`.