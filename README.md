# Spring Boot App

There repository contains a simple example of spring boot application. It contains simple controller which serves 
HTML page. The .css and .js files are used as well. Finally, it contains a controller test.


## Run tests

The Java 17 and the latest version of Maven should be installed on your PC before following the steps below. 
Alternatively, you can change a Java version in pom.xml.
  
* Clone repository
```bash
git clone https://github.com/vznd/spring-boot-app
```
  
* Go to a project directory
```bash
cd spring-boot-app
```
  
* Run tests
```bash
mvn test
```


## Run application

* Build jar
```bash
mvn clean package spring-boot:repackage 
```

* Start the app
```bash
mvn spring-boot:start 
```

* Access it in your browser following the [http://localhost:8080](http://localhost:8080/) URL


## Resources

* SpringBoot Guide [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)  
* The [gs-serving-web-content](https://github.com/spring-guides/gs-serving-web-content) repository on GitHub

