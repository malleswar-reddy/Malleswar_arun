Malleswar_Arun  study

## Table of Contents

- 1) @Rest Controller (#Rest Controller)
- 2) @Request Mapping (#Request-Mapping)

## Swagger2

https://www.programmersought.com/article/683793165/


* @Apilgnore: Use this annotation to indicate that Swagger2 ignores this API
* @ApiOperation : A method describing the class, or an interface

## Spring 
  * @configuration
    
      Spring @Configuration annotation helps in Spring annotation based configuration. @Configuration annotation indicates that a class declares one or more @Bean methods and may be processed by the Spring container to generate bean definitions and service requests for those beans at runtime.

* @EnableConfigurationProperties 
     
     Spring EnableConfigurationProperties annotation is strictly connected to @ConfiguratonProperties. It enables support for @ConfigurationProperties annotated classes in our application. However, it's worth to point out that the Spring Boot documentation says, every project automatically includes @EnableConfigurationProperties

* Spring Framework - @Async and @EnableAsync Examples
    
   + <https://dzone.com/articles/spring-boot-creating-asynchronous-methods-using-as>

##  spring Boot 

[@currentuser](https://stackoverflow.com/questions/31159075/how-to-find-out-the-currently-logged-in-user-in-spring-boot)

@ConfigurationProperties
  In Spring Boot, the @ConfigurationProperties annotation allows us to map the resource files such as properties or YAML files to Java Bean object.

This annotation is applied to a class or a @Bean method in a @Configuration class to map or validate the external properties or YAML files.

application.properties
```
myapp.mail.to=sunil@example.com
myapp.mail.host=mail.example.com
myapp.mail.port=250

```
Example code   

```@ConfigurationProperties(prefix="myapp.mail")
public class MailProperties {

  private String to;
  private String host;
  private int port;

  //Setter and getter methods
}
```
  <https://www.boraji.com/spring-boot-configurationproperties-example>

## Spring Mvc

@controlleradvice   

### Rest-Controller

  Create Rest api we can use 

  * spring Mvc
    1. @Rest controller
    2. @ExceptionHandler annotation is used for handling exceptions in specific handler classes and/or handler methods.[reference](https://spring.io/blog/2013/11/01/exception-handling-in-spring-mvc)


###   SLF4J  Simple Logging Facade for Java

 * [@Sif4j](http://www.slf4j.org/docs.html)


### Project Lombok

  * [@Data - Project Lombok](https://projectlombok.org/features/Data)

    @Data is a convenient shortcut annotation that bundles the features of @ToString , @EqualsAndHashCode , @Getter / @Setter and @RequiredArgsConstructor together: In other words, @Data generates all the boilerplate that is normally associated with simple POJOs (Plain Old Java Objects) and beans: getters for all fields

  * [@ToString](https://projectlombok.org/features/ToString)

        @ToString annotation enables you to avoid having to manually write a toString() method while inspecting fields for your objects.

    
  
