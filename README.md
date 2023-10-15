Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.
![image](https://github.com/hameez2002/calculator/assets/107755315/21c58800-21b5-4b3b-8ba4-6cab11db8a1c)

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

