[<< Back](/README.md)

# Microservices over Monolith
* Context  
Microservices are more future-proof than monolithic applications.

* Decision  
We decided to build microservices in order to maximise the scalability of our application. We are dependent on growth in order to succeed, and our services therefore need to be flexible and scalable.

* Status  
The stakeholders agreed with the plan; they agree that we need to be as future-proof and scalable as possible.

* Consequences  
Our core developer team is still relatively small; we're trading initial overhead for eventual scalability.

# PayPal integration via library
* Context  
We don't have capacity at the moment to maintain an in-house payment system.

* Decision  
We decided to use the well-established PayPal integration library "Super
Library" for this purpose instead of reinventing the wheel.

* Status  
Accepted after a demonstration showed that the implementation is correct for our
use case.

* Consequences  
We cannot control the details of the implementation.

# Spring Boot as our Backend Technology
* Context  
We have in-house developer experience

* Decision  
Because of the existing resource of developer experience and the widespread usage of Spring Boot, we decided to build our backend with this framework.

* Status  
Accepted after a meeting with the stakeholders; they were of the opinion that using our existing experiences was the correct approach.

* Consequences  
If any problems or incompatibilities between other services and technologies appear, we will have a hard time reimplementing the backend.

# Amazon CloudWatch as Analytics Software

* Context   
Our cloud provider is AWS and has a vast product variety. Used for monitoring resource usage. 

* Decision  
For ease of use and fast integration, we stay with Amazon since they are also our cloud provider.

* Status    
Not fully accepted. Approval missing in reagard of costs and neccessity. There is demand from the development team. 

* Consequence   
Adds another layer of tasks for our development team.   
Increase of costs.   
We are even more dependent on a single provider.        
Helps gather statistics and numbers not only for developer but also for business partners.
