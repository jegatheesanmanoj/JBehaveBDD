Amazon - Books Project

Project Description: Automation framework to go to Amazon.com and search for 'Data Catalog' in books category. In results page, capture information for a specific record in result. Project is developed using the below:

Serenity BDD - v1.5.11 (Open source wrapper library written based on JBehave and Selenium)
Junit - 4.11
Maven
Test Framework: Serenity BDD: Serenity is an open source library that helps to write higher quality automated acceptance tests faster.

Website: http://www.thucydides.info/

Reason to select serenity bdd:

Easy to setup and write acceptance tests
Use of JBehave bdd enables non-technical testers to extend and write new tests with minimal knowledge
Powerful reporting library
Easy to scale in terms of tests
Programming Language: Java - jdk1.8

Browser: Firefox v57

Geckodriver: v0.19 64bit

Design:

Create BDD - gherkin style tests in .story files
Create Step definitions to call step implementations for earch gherkin step
Create step implementations
Create Page object class to maintain page elements and action methods
Include Junit assertions in Steps class where necessary
Execution instruction:

Command line: mvn -f "pom file path"\pom.xml clean integration-test verify

--or--

Run Configuration:

Right click project and click Run as
Select Maven Build
Enter goals - clean integration-test verify
Click Run
Report location: index.html under 'target\serenity\serenity-reports' folder in project
