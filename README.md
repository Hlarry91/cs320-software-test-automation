# cs320-software-test-automation
CS 320 Software Test Automation and QA projects including Contact, Task, and Appointment services with JUnit testing

## This repository contains selected artifacts from CS 320: Software Test Automation and Quality Assurance. The included files demonstrate my ability to design validated domain models, implement service-layer logic, and develop unit tests using JUnit to verify requirements.

## Reflection

### How do I ensure that my code is functional and secure?

I ensure my code is functional by translating requirements directly into test cases. For each constraint, such as field length limits or null validation, I implemented corresponding unit tests to confirm both valid and invalid behaviors. Using JUnit allowed me to validate object construction, exception handling, and service-layer operations in a controlled environment.

From a security perspective, input validation is a foundational practice. Enforcing strict constraints on IDs, strings, and dates reduces the likelihood of invalid or unsafe data entering the system. I approach security by preventing improper states rather than attempting to correct them after the fact.

### How do I interpret user needs and incorporate them into a program?

I interpret user needs by carefully analyzing documented requirements and translating them into measurable rules within the code. In this project, each specification requirement was implemented as a validation rule or service operation. By designing tests around those requirements, I ensured that the system behavior aligned with expected outcomes.

I also recognize that interpreting user needs requires clarity and structure. Breaking requirements into smaller components allows for focused development and testing, reducing ambiguity and improving reliability.

### How do I approach designing software?

I approach software design with modularity and testability in mind. Separating domain objects from service classes allowed me to isolate validation logic from data management. This separation improves readability, maintainability, and ease of testing.

Writing unit tests alongside implementation encouraged me to think critically about edge cases and failure states. While this project primarily focused on unit testing, it reinforced the importance of designing software in a way that supports verification and long-term maintainability.
