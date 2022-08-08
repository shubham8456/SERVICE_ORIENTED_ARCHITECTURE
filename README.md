# SERVICE ORIENTED ARCHITECTURE

## WHAT IS SERVICE ORIENTED ARCHITECTURE

Service Oriented Architecture, or SOA, is a style of software design where services are provided to the other components by application components, through a communication protocol over a network. Its principles are independent of vendors and other technologies. In service oriented architecture, a number of services communicate with each other, in one of two ways: through passing data or through two or more services coordinating some activity [^1].

SOA defines a way to make software components reusable via service interfaces. These interfaces utilize common communication standards in such a way that they can be rapidly incorporated into new applications without having to perform deep integration each time [^2]. Each service in an SOA embodies the code and data integrations required to execute a complete, discrete business function (e.g., checking a customer’s credit, calculating a monthly loan payment, or processing a mortgage application). The service interfaces provide loose coupling, meaning they can be called with little or no knowledge of how the integration is implemented underneath. The services are published in a way that enables developers to quickly find them and reuse them to assemble new applications. These services can be built from scratch but are often created by exposing functions from legacy systems of record as service interfaces.

## HISTORY OF SOA

SOA represents an important stage in the evolution of application development and integration over the last few decades. Before SOA emerged in the late 1990s, connecting an application to data or functionality housed in another system required complex point-to-point integration—integration that developers had to recreate, in part or whole, for each new development project. Exposing those functions through SOA eliminates the need to recreate the deep integration every time[^2].

![Before and After SOA](https://miro.medium.com/max/1220/1*QpkU690MioKK7lHwLE0_Bg.png)

## ADVANTAGES OF SOA[^3]

* **Service reusability:** In SOA, applications are made from existing services. Thus, services can be reused to make many applications.
* **Easy maintenance:** As services are independent of each other they can be updated and modified easily without affecting other services.
* **Platform independent:** SOA allows making a complex application by combining services picked from different sources, independent of the platform.
* **Availability:** SOA facilities are easily available to anyone on request.
* **Reliability:** SOA applications are more reliable because it is easy to debug small services rather than huge codes
* **Scalability:** Services can run on different servers within an environment, this increases scalability

## DISADVANTAGES OF SOA

* **High overhead:** A validation of input parameters of services is done whenever services interact this decreases performance as it increases load and response time.
* **High investment:** A huge initial investment is required for SOA.
* **Complex service management:** When services interact they exchange messages to tasks. the number of messages may go in millions. It becomes a cumbersome task to handle a large number of messages.



### REFRENCES
[^1] : [What Is Service-Oriented Architecture?](https://medium.com/@SoftwareDevelopmentCommunity/what-is-service-oriented-architecture-fa894d11a7ec), Feb 13th, 2019 
[^2] : [Service Oriented Architecture](https://www.ibm.com/in-en/cloud/learn/soa) by IBM Cloud Education , July 17th, 2019
[^3] : [Service Oriented Architecture](https://www.geeksforgeeks.org/service-oriented-architecture/) by geeksforgeeks, Aug 29th, 2021
