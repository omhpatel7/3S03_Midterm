# Week 2 - Lecture 1

## Section 4: What and When Should You Test?

- **Unit testing**: this technique is used for testing the smallest meaningful parts (i e., the units) of your code.

    - can help find low-level faults
    - easy implementation

- **System testing**: the technique of testing the system as a unified whole.

    - easy to find fault w.r.t our design intent
    - tests functional and non-functional requirements
    - less effective at identifying small, localized faults 
    - slower / complex to implement

- **Integration testing**: different units, modules, or components of a software application are tested as a combined entity to see how they behave with each other.

    - uses black-box approach during testing
    - **big bang** means  put everything together then test
    - **top-down** approach take modules tested from the entry points and integrated progressively
    - **bottom-up** modules are progressively integrated and tested from the most elementary ones
    - find faults which unit tests cannot
    - much easy to versatile than system testing

- **Acceptance testing**: evaluating a software system to ensure it meets the specified business requirements and user needs before it is released.

    - help build trust with customer
    - help understand customer and market

- **Smoke testing**: basic tests that check the basic functionality of an application. Their goal is to ensure that the major features work as expected.

    - a scenario when we use smoke testing is when we finished making something and want to decide whether or not we can run more expensive tests

- **Regression testing**: re-running tests to ensure that previously developed and tested software still performs as expected after a change.




