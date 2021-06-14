# Translink# Minimum Requirements
java --version ==> 15.0.1
Eclipse IDE
Chrome browser --version ==> 91.0.4472.101
Chromedriver --version ==> 91.0.4472.101


# Test Automation Project

This is the test automation project based on Selenium-Webdriver with Java. This is built as a maven project and all the required dependencies are specified in pom.xml
The weburl used in this project is https://www.translink.ca/. The test includes navigating to different pages on the translink website 
and validating the actions performed by the user  


# Project Structure
Here you can find a short description of main directories and it's content
-[src/test/java/Pages](*pages) - for every page there is a repespective page class created and all 
the webelements correspoding to that particular page are identified. The actions performed
[src/test/java/Pages](logsetup) - loggin setup is intialised in logsetup class 
on the particluar page are created using the functions
-[[src/test/java/Testcases](testbase) - there is a testbase class created where the driver is instantiated 
-[src/test/java/testcases](testscenario) - All the required validations are performed in this class 
-[src/test/resources](*properties) - log4j properties file 


# Project Features
- framerwork implemented in this project follows, page object model pattern
- testng has been used for running the tests and generating the html reports 


# Run Automated Tests
- run the Eclipse IDE and open the existing project into the workspace 
- right click on the project and select runas testng suite 

# Test Report
-[test-output](index.html) - Testng provides with default html reports 

# Logs
-[logs](Mylog.log) -  Log information is recorded





