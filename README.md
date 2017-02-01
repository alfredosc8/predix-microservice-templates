<a href="http://predixdev.github.io/predix-microservice-templates" target="_blank">
	<img height="50px" width="100px" src="images/pages.jpg" alt="view github pages">
</a>
Predix Microservice Templates
==============

Welcome to Predix Microservices Templates.  Predix Microservice Templates contains 3 sub-projects that contain best practices for creating back-end Microservices. 

| Project |  Note | 
| ------------- | :----- |
| [predix-microservice-cf-spring](https://github.com/PredixDev/predix-microservice-cf-spring) | a java spring microservice template |
| [predix-microservice-cf-jsr](https://github.com/PredixDev/predix-microservice-cf-jsr) | a java jsr REST service microservice template |
| [predix-boot-dsp-cf](https://github.com/PredixDev/predix-microservice-templates) | will be deprecated in June 2016 |
| [predix-microservice-cf-rabbitmqconsumer](https://github.com/predixdev/rabbitmq-consumer-template) | a java rabbitmq consumer microservice template |

Each project shares the following characteristics
* Test cases and test case framework 
* Externalized Properties files
* REST implementation and framework
* Cloud ready with a Manifest file
* Environment Aware for Local, DEV, QA, Stage, Prod
* Continuous Integration capable

## predix-microservice-cf-jsr

This project is a cloud-ready microservice that demonstrates how to create [JSR - CXF](https://cxf.apache.org/) based Services.  You simply change the @Path url and begin adding your service implementation.  It has SpringBoot, Spring Profiles and Property file management configured and ready for local development vs. cloud deployment.  It is also set up for Test Driven Development with JUnit and Mockito.

## predix-microservice-cf-spring

This project is a cloud ready microservice that demonstrates how to create a [Spring](https://spring.io/) RestTemplate based REST services.  You simply change the @Path url and begin adding your service implementation.  It has SpringBoot, Spring Profiles and Property file management configured and ready for local development vs. cloud deployment.  It is also set up for Test Driven Development with JUnit and Mockito.

Once you are familiar with the project you are interested in and ready to make your own microservice, use the project as your starting point for a Cloud Foundry Rest Microservice. Change 'predix-microservice' to 'my-servicename' everywhere (using eclipse) and check in to your own repo.

###predix-boot-dsp-cf
>For Predix users migrating from older predix systems, the predix-boot-dsp-cf has all the features of predix-boot-cf, and it brings a backward compatible bundle from a non-cloud Predix implementation to the cloud simply by adding a dependency to your old rest service code.  If you use Spring, you simply add the @ImportResource annotation to list the Spring XML files from your old project.  In other words, it's adding a cloud-foundry wrapper around your old Rest service, which suddenly makes it deployable to the cloud. 

##Microcomponents
Be sure to check out our Micromponent Utility projects which you'll like need to call Predix Services.

* [Predix Microcomponent Bootstraps](https://github.com/PredixDev/predix-rmd-ref-app/blob/master/docs/microcomponents.md) - reusable libraries that can be used in any microservice

[![Analytics](https://ga-beacon.appspot.com/UA-82773213-1/predix-microservice-templates/readme?pixel)](https://github.com/PredixDev)
