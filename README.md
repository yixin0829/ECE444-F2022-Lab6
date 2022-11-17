# ECE444 F2022 Lab 6 - Test-Driven Development (TDD)

## Link to Unit Test Contribution in Team Project
- [Link](https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-18-caffeinated/blob/c93a3e73028948e8b66333bab4fda46e196d3c96/Education_Pathways/tests/test_course_reviews.py#L5-L21)

## Pros & Cons of TDD
### Pros
- TDD helps reduce the defect rate in production code
- The emphasis on refactoring leads to **better design quality** in source code
- Enable faster innovation and integration because of the resulting robustness in the code
- Code can be refactored easily or moved with little risk of breaking the code, leading to flexibility and extensibility
- Tests themselves are tested, with verifying test fails as part of the TDD process
- There's little to no wasted effort because during each iteration developers write minimal code to pass the requirements (tests)

### Cons
- People may forgot to run tests or write tests in consistent styles (overly complex or overly trivial) 
- TDD is not suited for cases like:
    - Large complex codebases
    - Source code that interacts with legacy system
- Overly long run times to run the test suites
