[<< Back](/README.md)

# Solution Strategy

1. The server application is written in Java.
   - Our core developer team has Java experience.
   - We will use the industry-standard Spring framework.
2. The clients are written in Flutter, which streamlines development for Android and iOS.
   - We have some challenges in this area: we do not have any in-house Swift experience.
   - Native code implies some doubled work.
   - The user experience must be seamless, which requires native code.
3. The client applications have feature parity with each other.
4. The clients communicate with the server via a well-defined API.
    - Flutter will help us to streamline our development process into a single codebase, in order to reduce code overhead and redundancy.
5. The system is designed as microservices.
    - We anticipate that there will be higher initial costs, but as our start-up expands, this architecture will enable individual teams to own and manage specific microservices.
6. The system is fully containerized to improve scalability, portability, and service isolation.
    - To address the issue of peak times, we adopt a microservices architecture for scalability.
7. The system is resilient; we are dependent on growth and must therefore plan for downtime solutions.
