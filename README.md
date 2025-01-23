# Unit Test KPI
GOAL:

Create system-wide KPI on base of unit tests

The report will executed periodically 

The report will analyze a set of given classes (packages) and output the following information:
* package
* number of classes
* number of classes with unit tests
* number of unit test methods
* number of classes with more than x test classes
* number of test classes with more than x test methods
* number of successful unit tests
* number of failed unit tests
* ratio classes/ test classes
* ratio classes/ test methods
* ratio test classes/ test methods
* percentage of code coverage
* ratio class/ code coverage

the result will be stored in a separate database table

# Usage

Teams can define goals like
* increase the number of classes with unit test from 10 to 100
* increase the ratio of classes with unit tests from 1% to 5%

# UI

Build SAPUI5 application to visualize the data
