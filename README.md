# README.md
# TestMersys
![Maven Central](https://img.shields.io/maven-central/v/org.seleniumhq.selenium/selenium-java?versionSuffix=4.11.0&label=Selenium)
![Maven Central](https://img.shields.io/maven-central/v/io.cucumber/cucumber-java?versionSuffix=7.9.0&label=Cucumber)
![Maven Central](https://img.shields.io/maven-central/v/org.testng/testng?versionSuffix=7.7.0&label=TestNG)
![Maven Central](https://img.shields.io/maven-central/v/org.slf4j/slf4j-api?versionSuffix=1.8.0-beta2&label=Slf4j)
![Maven Central](https://img.shields.io/maven-central/v/org.apache.commons/commons-lang3?versionSuffix=3.12.0&label=Apache%20Commons)
![Maven Central](https://img.shields.io/maven-central/v/tech.grasshopper/extentreports-cucumber7-adapter?versionSuffix=1.9.2&label=Grashopper)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

I use JAVA, TestNG, Cucumber, Gherkin and other JAVA Tools on this project.

Domain: https://test.mersys.io


Getting Started
---------------

The easiest way to get started is to clone the repository:

```bash
# File > New > Project From Version Control 
# Copy to URL
https://github.com/rustem626

# open project at Intellij
# select project JDK
jdk1.8

# Load Pom
Click to pom.xml > Maven > Reload Project

# Run All Test
Click to Runners > TestRunnerAll and Run

# Run Cross Smoke Test
Click to Runner > TestRunnerSmoke and Run

```

List of Dependencies
----------------

| Package      | Description                           |
|--------------|---------------------------------------|
| TestNG       | Next Generation Testing Tool.         |
| Selenium     | Browser Automation Framework.         |
| slf4j        | The Simple Logging Facade for Java.   |
| commons.io   | The Apache Commons IO library.        |
| cucumber     | Cucumber is a tool that supports BDD. |
| grasshopper  | HTML & PDF Report tool.               |

## File Structure
```bash
|-- src
|   |-- main
|       |-- java
|       |-- resources
|
|   |-- test
|       |-- java
|           |-- FeatureFiles
|               |-- Cucumber Feature Files
|           |-- PageObjectModels
|               |-- Locators, Page Object Model Files
|           |-- Runners
|               |-- TestRunnerAll
|               |-- TestRunnerHR
|               |-- TestRunnerLogin
|               |-- TestRunnerRegression
|               |-- TestRunnerSmoke
|           |-- StepDefinitions
|               |-- Hooks
|               |-- * Test Class Files
|           |-- Utilities
|               |-- BaseDriver
|               |-- Events
|               |-- ExcelUtility
|       |-- resources
|       |-- results
|           |-- reports*
|           |-- .gitignore
|
|-- .gitignore
|-- pom.xml

```

## Rules Of Pull Request
- Update your codes from main branch before you pull request
- Don't use Thread.Sleep
- Don't use Turkish Character
- Don't use extra space
- Use logical comment lines

## Team
- Emrullah Tanıma - Team Lead
- Samet Çamoğlu - Tester
- Ümit Boyraz - Tester
- Selen Dilek - Tester
- Rustam Roz - Tester
- Umut Can Güzel - Tester
- Yakup Yüce - Tester

## License

This project is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).


### Enjoy! 👋

