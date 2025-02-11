# Week 4 - Lecture 1

## Test-Driven Development (TDD)

What difficulties do you have when programming?

- Fear of changing our code
- Confusion
- Anxiety (how to solve the problem????)
- Despair (loss of hope <--just like me for this midterm)

TDD has 3 main parts: $\\$

**Refactor** $\rightarrow^{\text{Identify missing
functionality and write a test}}$ **Failing Tests** $\rightarrow^{\text{Write just enough
code to pass the test}}$ **Passing Test** $\rightarrow^{\text{Identify code smells}}$ **Refactor**

**Refactoring**: means to change the code to improve its structure, while not affecting its behaviour.

- This is done to improve the quality of our code, to make it easier to understand, and to facilitate future changes.


**Code Smells**: Not code violations per se, but clear indications of subpar code

- Bascially means that don't have shit looking code.
- Have good names for variable, functions, classes, and etc. 
- Don't have everything in one function.
- Do not duplicate code (have same var names, same func names, etc).


## Advanced strategies for large (real) systems

**Test Double**: is a generic term for any case where you replace a production object for testing purposes.

- **Dummy**: objects that are passed around but never actually used.

    - used to fill in parameter lists to make the code compile or run.
    - example of this is when a method requires an object as a parameter, but you don’t need it for the test, you pass a "dummy" object (e.g., null or an empty object).

- **Fake**: objects with working implementations, but they are simplified or incomplete.

    - mimic real objects but are not suitable for production.
    - assume a in-memory database that stores data temporarily instead of using a real database. It’s faster for testing but not robust enough for production.

- **Stubs**: objects that provide predefined responses to method calls.

    - they simulate specific behaviors or responses during tests.
    - assume that a payment gateway stub that always returns "Payment Successful" for testing checkout functionality.
    - **Spies**: they are stubs that record information about how they were called.

        - they help verify interactions with the object during tests.
        - an email service spy that records how many emails were sent and what their content was.

- **Mocks**: objects that are pre-programmed with expectations about how they should be used.

    - they verify that the code interacts with them correctly.
    - example is of a mock payment gateway that expects exactly one call to processPayment() and throws an error if it’s called more than once or not at all.
