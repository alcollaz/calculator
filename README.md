[![Board Status](https://dev.azure.com/demobog/3e6af98c-e10c-4e1f-a26d-54cef4161e72/9561ff76-a44d-4e60-bc04-fa2484dacaed/_apis/work/boardbadge/94bca8c1-559e-4256-97ce-1b48a32536a1)](https://dev.azure.com/demobog/3e6af98c-e10c-4e1f-a26d-54cef4161e72/_boards/board/t/9561ff76-a44d-4e60-bc04-fa2484dacaed/Microsoft.RequirementCategory)
Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

