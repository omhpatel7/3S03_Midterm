# Week 1 - Lecture 3

## Section 3: Types of testing

- **Dynamic Testing**: Testing code by executing it.

    - Examples:

        - **Apache web server**: make a request generator that hammers a standard web site.
        - **Smartphone app**: give to target users to try out – monitor their confusion and the app’s crashes
        - **Satellite code**: put whole code in simulated environment, and try with expected operating cycles (at least one orbit, but multiple is better)

- **Static Analysis**: Testing code without executing it.

    - Examples:

        - **Apache web server**: extract an arch model and calculate load on components under various circumstances – where is the bottleneck?
        - **Smartphone app**: use tools to search code for patterns commonly associated with security vulnerabilities (e.g. buffer overflows)
        - **Satellite code**: rigorous structured inspection of whole code base – after all, you can’t retrieve satellite once it’s up there


- **Black-box testing**: testing without any knowledge of the software’s implementation.

- **Grey-box testing**: testing that exploits (partial) knowledge of the system to design tests for it.

- **White-box testing**: testing that systematically exploits knowledge of the system to design tests for it.

- **Functional testing**: testing that checks whether the program provides some specific functionality.

- **Non-functional testing**: testing that assesses the program on something other than whether it provides some function.

- **Fault** -> **Error** -> **Failure**:
    
    - Fault is a defect or flaw in the software that causes errors and leads a program to fail it's necessary goal. 
    - Error is a state caused by fault during the execution of a program which may result to abnormal outcomes.
    - Failure is when a software behaves unexpectedly from the user’s perspective or fails to meet intended goal.




