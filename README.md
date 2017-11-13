# Test-Coverage
Test Coverage repository is a helpful documentation resource to have a better understanding of what Test Coverage really is!

## What is test coverage?
Test Coverage measures the amount of testing executed .
-It give the information about covered and uncovered areas in the testing.
-100% coverage does not mean 100% tested.
-% of coverage =(no of test areas covered / total number of test areas)*100.
![alt](http://istqbexamcertification.com/wp-content/uploads/2012/01/test-coverage-formula.jpg)


## Why is test coverage useful?
1-To find the areas which are in the requirements document but not covered in the test cases .
2-It help to take decision about quality of product.
3- It help us to bridge the gap between requirement and test cases.

## What are Istanbul and NYC?
### Istanbul:
A JavaScript code coverage tool written in JavaScript, with a purpose to report what lines, functions and branches did your TDDs cover, including both unit tests, integration tests and also browser tests.
In other words, it's a tool that have been built to scale the amount of code that you are testing, which is computed over the compiler output not the original source code.

### NYC:
it's the NEW Istanbul command line interface, which have replaced the old Istanbul tool bin, in NYC, you can get reports on different scopes by using different command line flags, for example: --all flag will be examine all files that you have inside your project folder, and deal with them as they are JS files, which may(will) throw errors and make your test fail, from here comes the turn of Typescript compiler (you can find a resource to know more about it in references. below.)
more and more, NYC is the easiest way to get a code coverage no matter the number of frameworks you are using, or how many subprocess you have in your code.

## How would you use them to improve your testing?
Istanbul/NYC methodology of testing exists to tell programmers what and where the tests they have designed work, consider it as a map that tells you which ways you have completed and which you have not, how many steps have you been walking, and how many steps are left until you finally have tested everything properly.
less talk, this is just another tool to support JavaScript programmers to keep tracking their code testing and know how well they have done it.

## Use Istanbul/NYC to calculate your code coverage for the TDD workshop.
Mohammed is gonna play it live!



## Resources:
What is test coverage?: http://istqbexamcertification.com/what-is-test-coverage-in-software-testing-its-advantages-and-disadvantages/
Test coverage: https://www.youtube.com/watch?v=NmIB2tfshyY
Official website: https://istanbul.js.org/
NYC and Typescript: https://github.com/istanbuljs/nyc/pull/326
