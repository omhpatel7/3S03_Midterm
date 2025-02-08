# [Integration Testing](https://martinfowler.com/bliki/IntegrationTest.html)

### <ins>What is Integration Testing</ins>

Integration testing checks if different software components work together. Furthermore, it ensures that modules are communicating correctly with each other, while ensuring that the entire system works as expected.


### <ins>Narrow vs. Broad Tests</ins>

- Narrow Integration Testing:
    
    - This testing focuses on one component’s interaction with external services (e.g. APIs, databases).
    - It uses test doubles to mimic dependencies, avoiding slow, complex setups.
    - It is quick like unit tests and finds issues early in pipelines.
    - An example of this is when testing a shopping cart’s code that talks to a mocked catalog service.

- Broad Integration Testing:

    - This testing will test the entire system with live services, networks, and databases.
    - It is very slow, complex, and prone to failures (e.g. network timeouts).
    - This is usually used with **end-to-end** or **system tests**.

- Which is better?

    - When it comes to speed and reliability, narrow integration testing is used.
    - Narrow integration is also easier during debugging. It also ensures that test doubles behave like real services.


### <ins>Final Remarks</ins>

It is better to use **narrow integration tests** for focused interaction tests, and **system tests** for full-system validations. Also, prioritize narrow tests for speed and reliability.