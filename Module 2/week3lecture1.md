# Week 3 - Lecture 1

## Section 1: Software development happens in many different worlds

- We need to think about how we test based on the project and context.
- **PhonePicture**:

    - Manage pictures on your phone!
    - Send them to your friends!
    - Rate photos online!
    - Win prizes!
    - Your private photos are encrypted!

This app seem's like **instagram**.

## Section 2: Testing techniques

**Exploratory testing**: simultaneous learning, test design, and test execution.

- helps discover unexpected behaviors or issues
- helps understand of the software

**Specification-based testing**: testing software against all the explicit claims made about it in the specification.

- ensure the software meets its documented requirements
- captures what matters most about the software

**Model-based testing**: using models of expected behavior to produce testcase specifications that can reveal discrepancies between actual program behavior and the model.

- simple terms: test a program specified by a model to find faults
- helps uncover edge cases and unexpected behaviors

**Fuzz testing**: testing by feeding in random inputs until the program crashes or violates assertions.

- helps discover vulnerabilities, crashes, or unexpected behaviors
