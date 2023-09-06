# Cypress-BDD-Automation
This repository contains Cypress Automation with BDD cucumber and Page object model framework for Healthcare Project

**Tools and Technologies**

Language: JavaScript Automation Framework: Cypress Reporting: Mochawesome

## Folder Structure are as Follows:

e2e Folder: contains all features files
fixtures Folder : contains config file
page_objects Folder : contains all pages and implementation
Step_definitions Folder : contains all steps file with implementation

## Framework To be used:

The test automation framework follows a Page Object Model (POM)-like structure to enhance code reusability, maintainability, and readability. It's designed to organize test scripts, 
Page object model, Behavior Driven Approachand verification methods efficiently.

BDD Cucumber
Page object model
Gherkins language
Mochawsome Report

### Approach & Techniques 

Use of Backgroud Keyword
Scenario/s
Scenario with Data Table Examples
Scenario Outline with Examples
Gherkin Tagging

**Setup and Execution Steps**

git clone https://github.com/Razacs/Cypress-BDD-Automation.git

npm install //Install Dependecies

Run all test form default electorn browser thorugh cypress in headless mode

-> npx cypress run

Run all tests in chrome browser headed mode

-> npx cypress run --headed --browser chrome
-> npx cypress run --headed --browser electron

Run cypress with specificed tag with headless mode with default electorn browser

-> npx cypress-tags run -e TAGS='@smoke'

Run cypress with specificed tag with chrome browser headed mode

-> npx cypress-tags run -e TAGS='@regression' --headed --browser chrome


