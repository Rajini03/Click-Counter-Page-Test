This project automates testing of the Click Counter page using Behavior Driven Development (BDD) with Selenium WebDriver.

STEPS:

* Create a new Maven Project
* Set up Maven dependencies by specifying the required libraries in the pom.xml file. Add Selenium, JUnit, Cucumber, and WebDriver Manager dependencies.
* Install Cucumber Plugin: This plugin allows us to use Gherkin syntax in ".feature" files for BDD testing.
* Create a Feature File
* Create Step Definitions
* Explanation in detailed intitial state, action perfomed, verifying the result.
* Run the test using Junit Runner to excute the BDD test.
* Test Execution: Once the tests are executed, a chrome browser will open and navigate to the specified page, perform the click action, and validate the result based on the counter value. Here if we need to generate reports after the test runs using Cucumber's reporting features.
