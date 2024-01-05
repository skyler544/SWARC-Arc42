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
5. The system is designed as microservices.
6. The system is fully containerized to improve scalability, portability, and service isolation.
7. The system is resilient; we are dependent on growth and must therefore plan for downtime solutions.
