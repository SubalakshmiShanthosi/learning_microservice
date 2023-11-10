# Introduction

What is microservice architecture?
- Approach to build software systems => decomposes business domain models into **smaller, consistent and bounded-context** implemented by services.
- Services are isolated and autonomous yet communicate to provide a piece of business functionality.
- This type of development is opted by companies with smaller teams  - each team working and building separate microservice with enough autonomy to change the internal implementation details with minimal impact across the rest of the systems
- Independence aids agility - teams communicate through promises, which is a way a service can publish intentions to other components or system that may wish to use the service.
- They specify these promises with interfaces of their services and via wikis that document their services.

Why microservices architecture? 

- We can **scope the boundaries of the service**
- Understand what the service is doing without being tangled into other concerns in a larger application.
- Quickly build the service locally.
- Pick the right technology to implement the concerned service --> Work on reducing latency? or burst / waiting time? query optimization all of these items cant be focused to improve the quality of the service.
- Test the service
- Build or deploy or release the service at a cadence necessary for the business, which may be independent of other services
- Increase resiliency of the system as a whole
- Scale horizontally

Any cons for implementing microservice? 

Yes, we can think of microservices architecture as an optimization for the problems that require the ability to change things quickly at scale but with a price.
- It can be more resource intensive
- It can bring in duplication
- Increases operational complexicity to a larger extend
- It becomes difficult to understand the system holistically.

Challenges in building microservices? 
Designing cloud native applications following microservices approach need a different thinking on building, deploying and operating the system. 
In complex ecosystem - we cannot uncover all ways the microservice behave / failure cases -- we must be able to deal with **uncertainity**

Here are five things to keep in mind while building microservice - 


Designing for faults - Building distributed system has to deal with network errors and latency
