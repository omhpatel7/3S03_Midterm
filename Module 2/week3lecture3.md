# Week 3 - Lecture 3

## Section 3: You can classify testing techniques

- Exploratory testing **[black-box]** **[functional testing]** 
- Specification-based testing **[black-box]** **[functional testing]** 
- Model-based testing **[black-box]** **[functional testing]** 
- Fuzz testing **[black-box]** **[non-functional testing]** 
- Partition testing **[black-box]** **[functional testing]** 
- Boundary testing **[black-box]** **[functional testing]** 
- Coverage-based testing **[white-box]** **[functional testing]** 
- Fault injection **[grey-box]** **[non-functional testing]** 

All of the techniques above are dynamic testing techniques because they require executing the software to evaluate its behavior.

## Section 4: You can fit testing into any software lifecycle

- Waterfall Model:

    - Requirements -> Design -> Implementation -> Verification -> Maintenance

- How is testing typically performed?

    - Unit Testing -> Integration Testing -> System Testing -> Acceptance Testing

- Typical testing process and its artifacts include:

    - Requirement Analysis
    - Test Planning
    - Test Development
    - Test Execution
    - Test Reporting
    - Test Result Analysis

- Assume you've got venture capital and 12 months to bring PhonePicture to the market. How do you plan to do different testing activities across this time?

    - Phase 1:

        - Define requirements and create a test plan for functional and non-functional testing.
        - Set up testing environments, write unit tests, and conduct code reviews to ensure early defect detection.

    - Phase 2:

        - Perform integration testing to verify module interactions and use test doubles for external services.
        - Conduct system testing (functional, exploratory, performance, and security) to ensure the app works as a whole.

    - Phase 3:

        - Run alpha testing internally to fix usability issues and edge cases.
        - Release a beta version to external users for feedback and conduct exploratory testing to refine the app.

    - Phase 4:

        - Perform regression and compatibility testing to ensure stability across devices and platforms.
        - Conduct final performance and security checks and prepare for launch with app store listings and support documentation.

## Section 6: Quiz

1. What are three types of software systems that each need very different testing?

    - Embedded systems
    - Web applications
    - Mobile applications

2. What is exploratory testing?

    - A testing where the testers explore the application without predefined test cases. Testers find defects by interacting with the system, often discovering issues that might not have been anticipated in formal test cases.

3. What is specification-based testing aka requirements-based testing?

    - This type of testing is based on the specifications or requirements of the system. Test cases are designed to verify that the system behaves as expected according to the defined specifications.

4. In fuzz testing, the correct response to an input might not be known in advance. How can fuzz testing still be useful in this case?

    - The system is subjected to random or unexpected inputs to identify vulnerabilities, bugs, or unexpected behavior. Even though the correct response might not be known in advance, fuzz testing is useful because it helps uncover edge cases or weaknesses that might not be evident through traditional testing methods.

5. What effect does a pure waterfall development lifecycle have on testing?

    - Testing usually happens after the development phase. This can lead to problems being discovered later in the process, making them more expensive and time-consuming to fix. 

6. What’s a good reason to stop testing?

    - Many possible answers, but I would suggest defaulting to a combination of meeting basic coverage goals (statement coverage at the minimum) and getting consensus among the team.