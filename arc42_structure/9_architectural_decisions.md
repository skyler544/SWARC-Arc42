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
