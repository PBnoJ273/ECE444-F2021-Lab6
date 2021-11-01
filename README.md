# ECE444-F2021-Lab6
By: Puneet Singh Bagga

This repo is following the tutorial of https://github.com/mjhea0/flaskr-tdd

# Pros and Cons of TDD
TDD is a software development approach which focuses on creating tests then the code needed to pass them. It starts with developing tests for every small functionality of a given application then writing code if the test case fails (why fix it if it isnt broken). This ensures the application's functionality as it is being built and also the efficiency of the code being developed.

## Pros
  - Efficient Coding
    - Users only need to write code thats needed, since the your goal is to pass the test. This helps avoid duplicate code and forces the developers to write the most simple an least amount of code needed to pass a test or implement the feature
    - Offers less debuging since there is a less chance of breaking the code since the tests (as long as they are written well) will cover any bugs. This reduces the time in development and makes it more efficient overall.
    - Since users develop microfeatures and the test for them, it makes it easier to check (makes it more modular). Also the tests can act as documentation for the code since they show how things work and should work.
  - Code Maintainability
    - Since the application is developed is more modular, it makes maintainability much easier. Users can change features without affecting others (due to the TDD architecture) and therefore make it easier to swap implementations or develop more features without breaking the whole system.
  - Trustworthiness
    - Since there is a higher test coverage for every feature, we have more confidence in the functionality.


## Cons
  - Slow
    - Writing every test for every microfeatures takes a lot of time to do (depending on the size of a feature). Tests take time to come up with and implement so do the features after.
  - Difficult to Plan/Execute
    - Every member has to use TDD for it to be done efficiently. Since it also takes longer it will need a lot of thought in designing sprints.
  - Test Maintanence
    - Depending on the size of the project and feature updates, there could be thousands of tests that might need to be updated to support a new system. Reducing the overall maintainability of the software.


##
