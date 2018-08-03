# Spring Cloud - Cloud Native References
Following are some suggested references - books, courses, blogs, articles and videos to give a deeper dive into Spring Cloud 
and Cloud Native Developer courses:

## Some good overview Pluralsight courses
- Cloud Foundry for Developers: https://app.pluralsight.com/library/courses/cloud-foundry-developers/table-of-contents
- Pivotal Cloud Foundry for Developers: https://app.pluralsight.com/library/courses/cloud-foundry-developer-1dot7-pivotal/table-of-contents
- Java Microservices with Spring Cloud: Coordinating Services: https://app.pluralsight.com/library/courses/java-microservices-spring-cloud-coordinating-services/table-of-contents
- Java Microservices with Spring Cloud: Developing Services: https://app.pluralsight.com/library/courses/java-microservices-spring-cloud-developing-services/table-of-contents
- Git Intro: https://app.pluralsight.com/library/courses/how-git-works/table-of-contents
- Git Advanced: https://app.pluralsight.com/library/courses/mastering-git/table-of-contents
	
## Development & Design
- This site covers strategy of evolving applications from MVP (Minimum Viable Product, unstructured apps, through modularized monoliths, to distributed systems: http://www.appcontinuum.io/
- A great Spring One 2017 Talk about practical use of SOLID principles: https://springoneplatform.io/sessions/solid-in-the-wild-life-when-your-software-is-actually-soft
- Original 12 Factors: https://12factor.net
- "Beyond 12 Factors" (Pivotal evolution of original 12 Factors): https://content.pivotal.io/blog/beyond-the-twelve-factor-app
- "Components vs. Microservices, Independent Deployability": http://blog.cleancoder.com/uncle-bob/2014/09/19/MicroServicesAndJars.html

## Spring Boot Plugins (building and packaging Springboot Apps):
- Gradle Springboot Plugin: https://docs.spring.io/spring-boot/docs/2.0.1.BUILD-SNAPSHOT/gradle-plugin/reference/html/
- Maven Springboot Plugin: https://docs.spring.io/spring-boot/docs/current-SNAPSHOT/reference/htmlsingle/#build-tool-plugins-maven-plugin

## Spring Cloud on .NET
- Steeltoe (Spring Cloud Config Server and Spring Cloud Netflix on .NET): https://steeltoe.io/

## Netflix OSS Docs
### Ribbon (Client Load Balancing)
- Ribbon Wiki: https://github.com/Netflix/Ribbon/wiki

### Hystrix (Bulkheads and Circuit Breakers)
- Hystrix Wiki: https://github.com/Netflix/Hystrix/wiki
- Hystrix Algorithm: https://github.com/Netflix/Hystrix/wiki/How-it-Works
- Hystrix Metrics and Monitoring: https://github.com/Netflix/Hystrix/wiki/Metrics-and-Monitoring
- Performance Implications of using Hystrix: https://github.com/Netflix/Hystrix/wiki/FAQ%20:%20General#what-is-the-processing-overhead-of-using-hystrix
- Hystrix Operations and Tuning Guide: https://github.com/Netflix/Hystrix/wiki/Operations

### Eureka (Service Registry)
- Eureka Wiki: https://github.com/Netflix/Eureka/wiki

### Netflix Build Tools
- Nebula build plugins: https://nebula-plugins.github.io/

## Spring Cloud Netflix - Eureka, Ribbon, Hystrix
- Project Home: https://cloud.spring.io/spring-cloud-netflix/
- Product Documentation: http://cloud.spring.io/spring-cloud-static/spring-cloud-netflix/1.4.3.RELEASE/single/spring-cloud-netflix.html

## Spring Cloud Config
- Project Home: https://cloud.spring.io/spring-cloud-config/
- Project Documentation: http://cloud.spring.io/spring-cloud-static/spring-cloud-config/1.4.2.RELEASE/single/spring-cloud-config.html
- Spring External Configuration Orders of Precedence: https://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-external-config.html
- How to push config via git webhook: https://spencergibb.netlify.com/blog/2015/09/24/spring-cloud-config-push-notifications/
- Feature Toggles: https://martinfowler.com/articles/feature-toggles.html

## Spring Cloud Bus
- Home: http://cloud.spring.io/spring-cloud-static/spring-cloud-bus/1.3.3.RELEASE/single/spring-cloud-bus.html
- Targeting application for config bus refresh: http://cloud.spring.io/spring-cloud-static/spring-cloud-bus/1.3.3.RELEASE/single/spring-cloud-bus.html#_addressing_all_instances_of_a_service

## Spring Cloud Commons - Useful for seeing what's under the hood
- Project Home: https://cloud.spring.io/spring-cloud-commons/
- Projection Documention: http://cloud.spring.io/spring-cloud-static/spring-cloud-commons/1.3.2.RELEASE/single/spring-cloud-commons.html
- Ribbon Retry Policy: http://cloud.spring.io/spring-cloud-static/spring-cloud-commons/1.3.2.RELEASE/single/spring-cloud-commons.html#_retrying_failed_requests
- Service Registry - Ignoring Network Interfaces: http://cloud.spring.io/spring-cloud-static/spring-cloud-commons/1.3.2.RELEASE/single/spring-cloud-commons.html#ignore-network-interfaces
- Configuring Http Clients: http://cloud.spring.io/spring-cloud-static/spring-cloud-commons/1.3.2.RELEASE/single/spring-cloud-commons.html#http-clients
- Abstracting different Spring Cloud Service Registries: http://cloud.spring.io/spring-cloud-static/spring-cloud-commons/1.3.2.RELEASE/single/spring-cloud-commons.html#__enablediscoveryclient

## Pivotal Cloud Foundry & Spring Boot
### Injecting Creds to Spring Boot app
- An example of an easy way to do it: http://engineering.pivotal.io/post/spring-boot-injecting-credentials/
- VCAP Environment Post-Processor: https://docs.spring.io/spring-boot/docs/current/api/org/springframework/boot/cloud/CloudFoundryVcapEnvironmentPostProcessor.html
- An example of the hard way to do it: https://github.com/pivotal-education/pcf-articulate-code/blob/master/src/main/java/io/pivotal/education/articulate/service/EnvironmentHelper.java

## Pivotal Cloud Foundry - Spring Cloud Services
- Home: http://docs.pivotal.io/spring-cloud-services/1-4/common/index.html
- Dependencies Matrix: http://docs.pivotal.io/spring-cloud-services/1-4/common/client-dependencies.html
- Configuring Cross Cloud Foundry Service Registy (route mode): http://docs.pivotal.io/spring-cloud-services/1-4/common/service-registry/enabling-peer-replication.html
- GoRouter does honor Ribbon load balancing algorithm: http://docs.pivotal.io/spring-cloud-services/1-4/common/service-registry/connectors.html#instance-specific-routing-in-ribbon
- Configuring PCF Container-to-Container Networking, Service Registry and Client Load Balancing (SpringOne 2017): https://www.youtube.com/watch?v=1WJhFhBr-0Q

## Migrations & Monoliths
- "Online migration at scale blog": https://stripe.com/blog/online-migrations
- "Low risk monolith to micro services" Christian Posta: http://blog.christianposta.com/microservices/low-risk-monolith-to-microservice-evolution/
- "MonolithFirst" by Martin Fowler: https://martinfowler.com/bliki/MonolithFirst.html

## Blogs
- General blog of Cloud Native, Spring Cloud subjects from a Spring Cloud thought leader: https://spencergibb.netlify.com/
- Dipping into spring cloud topics from a Spring Cloud contributor: http://ryanjbaxter.com/
- The Spring blog: https://spring.io/blog

## Spring Cloud Dataflow documentation (handling streaming and data centric applications using cloud native patterns and tooling)
- Project Home: https://cloud.spring.io/spring-cloud-dataflow/
- Project Reference: https://docs.spring.io/spring-cloud-dataflow-samples/docs/current/reference/htmlsingle/
- Task Batch: https://docs.spring.io/spring-cloud-dataflow-samples/docs/current/reference/htmlsingle/#_task_batch
- Using PCF Job Scheduler: http://docs.pivotal.io/pcf-scheduler/1-1/using.html
- Project Home for Dataflow on PCF: https://cloud.spring.io/spring-cloud-dataflow-server-cloudfoundry/
- Project Reference for Dataflow on PCF: https://docs.spring.io/spring-cloud-dataflow-server-cloudfoundry/docs/current-SNAPSHOT/reference/htmlsingle/

## Books
- Release It! 2nd Edition: https://www.amazon.com/Release-Design-Deploy-Production-Ready-Software-ebook/dp/B079YWMY2V/ref=mt_kindle?_encoding=UTF8&me=&dpID=419zAwJJH4L&preST=_SX342_QL70_&dpSrc=detail
- Continuous Integration: https://www.amazon.com/Continuous-Delivery-Deployment-Automation-Addison-Wesley-ebook/dp/B003YMNVC0/ref=mt_kindle?_encoding=UTF8&me=&dpID=51yF2SYUi7L&preST=_SY445_QL70_&dpSrc=detail
- Building Evolutionary Architectures: https://www.amazon.com/Building-Evolutionary-Architectures-Support-Constant-ebook/dp/B075RR1XVG/ref=mt_kindle?_encoding=UTF8&me=&dpID=61kAEC%252BouJL&preST=_SY445_QL70_&dpSrc=detail

