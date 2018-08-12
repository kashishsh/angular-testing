Question: What is automated testing ?
Answer: - Automated testing is basically the practice of writing code to test our code and run those           tests in automated fashion. With automated testing, we can test a large part of
          application much faster than the manual tester.
        - With automated test, we can catch defects before releasing your software.
        - Be pragmatice while writing test cases.

Question : What are the type of tests ?
Answer : 1. Unit tests
         2. Integration test
         3. End to End test

Question: What are unit tests ?
Answer:
   - Test a component in isolation, without external resource (eg: file system, database, API endpoints). In angular terms, testing a component in isolation without its template and any other resources eg file system, database, api endpoints etc. If a component is using a service to talk to an api endpoint, you are gonna give it a fake instance of that service. we assume that service is doing its job properly and just wanna focus on the functionality of the component.
   - Easiest to write
   - Super fast
   - Don't give much confidence

Question: What are integration tests ?
Answer:
    - Test a component with external resources(eg: file system, database etc.)
    - Integration test in angular means testing a component along with its template. we need to look component as a whole along with the template.
    - We get more confidence with intergration tests.
    - We pass fake services to component rather than actual services.
    - We are testing implementation of component class with template.

Question: What are End to end tests ?
Answer: - Testing the application as a whole.
        - Here we simulate a real user.. launch the application in the browser and do some stuff.
        - Lot more confidence about application.
        - These test cases are very slow.
        - Very fragile




