# Design Plan for the @JRamos's Test Framework project.

## Objective

This project is designed to track my work while creating a fully-automated test framework, meaning that not only the tests are automated, but also the deployment and configuration of test environments, running of tests, tracking, and collection of results, etc.

## Description

Create a fully automated test framework that can be used for executing functional tests for Desktop applications, Web, and APIs.

The test framework will be built from the scratch. The framework must include:

* Automatic execution of the whole test cycle
  * This can be achieved using an automation server (eg.: Jenkins)
  * Must deliver a smoothy continuous integration and continuous delivery process 
* Deploy the execution environment
  * Deploy a docker image with its dependencies
  * Installation of the dependencies
  * Deploy necessary files
* Deploy of the test environment
  * Collection of test artifcats
  * Deploy of test targets (docker images, VMs)
  * Installation of dependencies
  * Installation of necessary software (webservers, browser, browser drivers, desktop apps, etc)
* Design of sample test cases
  * Design a couple of test suites and test cases to demonstrate the usage of the framework
  * Include at least one test suite for Windows Desktop Applicatio, one for UI Web Test and one for an API
* Execution of the tests
  * Tests must be executed when the test setup is completed
* Analysis of the results
  * Collection of the test data (screenshots, logs, reports, dump files)
  * Publish of the results (e.g.: on Jenkins, Slack, etc)

Some requirements for the test framework are:
* All steps should be fully automated. If not possible or not valuable, then a minimal amount of human intervention should be used
* Scalability should be considered from the very beginning
* Performance is a matter
* It should be easy to use for different user roles
* Documentation

## Time frame for the project
This is a personal project, but I want to have an MVP in less than two months. Considering the holidays, by the beginning of February. This will be specified after the creation of the issues 

## Expected results
An MVP that can be easily executed by anybody interested

## Starting date
I'm starting this project on December 7th, 2022. I want to have the MVP in the middle of February.
Good luck.
