# ECE444 F2022 Lab 6 - Test-Driven Development (TDD)

## Link to Unit Test Contribution in Team Project
- [Link](https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-18-caffeinated/blob/c93a3e73028948e8b66333bab4fda46e196d3c96/Education_Pathways/tests/test_course_reviews.py#L5-L21)

## Pros & Cons of TDD
Test-driven development is a software testing approach which focuses on an iterative process of writing software through continuous testing, refactoring, re(write) tests. Based on a [Educative's article about TDD](https://www.educative.io/blog/test-driven-development#tdd-advantages), most teams reported although TDD introduces a some overhead costs in the initial development effort, the overhead costs are offset by "reduced effort in the final phase of projects". Analytically this advantage could be valid. TDD encourages developers to write test cases before start developing any functionalities in the codebase, therefore the team will have a initial overhead to adopt this kind of testing approach. However, as the team matures and gets more familiar with the test suites created by a collective effort of all the team members, it enables faster innovation and integration as TDD makes the code more robust. The resulting code from using TDD approach also can be refactored easily or moved with little risk of breaking the code as developers can always run the tests after reorganizing the code to validate its working status. Lastly, there's little to no wasted effort because during each iteration developers write minimal code to pass the requirements (tests).

On the other hand, TDD can also be too idealistic as there are several potential downsides of using TDD. The main downside could be due to human factor. Indivually, it would be hard to ensure every developer writes test cases in a consistent fashion and how many tests to write at once. On a team level, the maintainance of test suites is usually labouring and leads to overly long run times during development. In the event of team turnover, the new team may also abandon TDD test suites.

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
