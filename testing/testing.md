# Testing

## General

Testing applications is a daily task for professional grade software developers and should be considered basic training.

## Manual testing

Manual testing is the process of using the feature that is under development and in order to do this in a modern web application you will need to know the browsers your company is supporting and the oldest version of that browser, each of these browsers should be part of your testing process if you are testing a user facing interface.

It is not uncommon that you will need to test on a range of devices as well.

You can read more about manual testing [here](https://en.wikipedia.org/wiki/Manual_testing).

## Regression testing

It is often a risk that a new feature being created will cause another part of the system to stop working correctly and the process of testing a new feature should always be followed by a regression test where you verify that you didn't break something that used to work correctly.

You can read more about regression testing [here](https://en.wikipedia.org/wiki/Regression_testing).

## Unit testing

Unit testing is the process of writing a test for a function in your code so you can verify that the function behaves as you expect.

You can read more about unit testing [here](https://en.wikipedia.org/wiki/Unit_testing).

## Test driven development (TDD)

TDD is a work process where you start by writing your test before you write your function and once the test is failing you write the logic that is needed to make the test pass.

You can read more about TDD [here](https://en.wikipedia.org/wiki/Test-driven_development).

## Integration testing

Integration testing is the process of testing a module of features or a flow of features e.g making a network call to the server and verifying that the correct functions are called.

You can read more about integration test [here](https://en.wikipedia.org/wiki/Integration_testing).

## Common testing libraries

* [Jest](https://jestjs.io/)
* [Mocha](https://mochajs.org/)
* [Sinon](https://sinonjs.org/)
* [Chai](https://www.chaijs.com/)
* [Enzyme](https://airbnb.io/enzyme/)

## Test automation

Test automation is the process of creating automated tests that verify that your system works.

At the time of writing this document this is a popular way to describe a automated test that interacts with the application as if a user was using it.

You can read more about test automation [here](https://en.wikipedia.org/wiki/Test_automation).

## Test automation tools

At the time of writing this document the following tools are useful to creating automated tests in [Node](../backend/node/node.md).

* [Cypress](https://www.cypress.io/)
* [Puppeteer](https://pptr.dev/)

## Behavior driven development (BDD)

BDD is the process of describing the desired behavior of a feature and implementing a automated test that can be used to verify when the feature has been completed.

This style of working is not as common in the industry but very effective for large application development.

You can read more about BDD [here](https://en.wikipedia.org/wiki/Behavior-driven_development).

## Useful BDD tools

* [CucumberJS](https://cucumber.io/)
* [Puppeteer](https://pptr.dev/)

## A/B testing

A/B testing is the process of creating a variant of a feature and only releasing it to a portion of the users who are using the application.

This is very common in large companies when the company wants to know if a new feature improvement will produce a better result than an already existing feature.

You can read more about A/B testing [here](https://en.wikipedia.org/wiki/A/B_testing).

**[back](../README.md)**
