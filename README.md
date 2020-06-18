# Oddball Quality Assurance Challenge
## Prerequisites
1. Shell of your choice
1. [Node.js / NPM](https://www.npmjs.com/get-npm)
1. *Preferred:* [GitHub account](https://github.com/join)

## Tasks
1. Clone this repository to your machine.
1. Analyze the user stories available in this repository, and create a test plan that provides coverage for the acceptence criteria described within the user stories. You will use a combination of manual functional test cases and automated tests to verify the acceptence criteria.
1. Create an automated end-to-end test that covers the core user journey per your analysis of the user stories.
1. Use the Cypress-->TestRail integration to record automated e2e test executions to your test plan.
1. Generate a reports within TestRail that provide
   *  A summary of all defects discovered by your test executions
   *  A report displaying traceability of user stories to test cases

## Tools
1. [TestRail](https://www.gurock.com/testrail/docs/user-guide/getting-started/walkthrough) -- A cloud hosted instance of TestRail is available for test management [here](http://oddball.testrail.io). It has been configured to reference user stories and record defects in this GitHub repository.
2. [Cypress](https://docs.cypress.io/guides/getting-started/writing-your-first-test.html) -- Automated test framework is included in this repository and preconfigured to point to Quizlet.com. Additionally, the [TestRail Reporter for Cypress](https://www.npmjs.com/package/cypress-testrail-reporter) is installed and configured to point to this repository.

## Artifacts
At the completion of the challenge you will deliver the following artifacts.
1. Test Plan
1. Test Execution Records
1. Summary of Defects Report
1. Coverage for References Report
1. Automated End-to-end Test Case
