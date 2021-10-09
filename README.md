# OC_MasterSeleniumFramework
With further updates - This project is designed and developed with the help of -
1. Udemy course (OmPrakash Chavan - Selenium Java Test Framework & Best Practices - Masterclass)
2. YouTube playlist (Testing Mini Bytes - Selenium Automation Framework with Real-time dashboard)

It has a concept of Atomic tests (Achieved by Selenium WebDriver API and RestAssured API)
------------------------------------------------------------
![image](https://user-images.githubusercontent.com/26399692/135917549-ee1e000a-ce07-4051-89b1-b57ec9b6b9b7.png)
------------------------------------------------------------
Updations done:
------------------------------------------------------------
**ExtentReports V5** 
1. User can apply the Filters - 
- Author - Rajat, Nishant, Gautam, Pankaj 
- Browser - Chrome, Edge, Safari, Firefox 
- TestType - Smoke, Sanity, Regression, BVT

2. Screenshots are attached in the Screenhot ad Base64 format.
![image](https://user-images.githubusercontent.com/26399692/135918483-ca9320af-83da-4b55-b3d7-24449cc1bd04.png)
![image](https://user-images.githubusercontent.com/26399692/135918943-a430a4fc-dd05-4803-9765-dbb94bb4fd89.png)

------------------------------------------------------------
**Allure Reports** 
![image](https://user-images.githubusercontent.com/26399692/135977881-10e654b4-6224-4aa9-8343-841af16aeeb3.png)
------------------------------------------------------------
**User has options for customization**
![image](https://user-images.githubusercontent.com/26399692/135927821-1e293278-14f2-4ad2-94dc-5505b080680d.png)
------------------------------------------------------------
**Email to User(s) using Java mail API**
![image](https://user-images.githubusercontent.com/26399692/135975570-d520d163-a7eb-4695-b22c-a25979415ef5.png)
------------------------------------------------------------
**Others:**
1. Retry failed test cases
2. Custom Enums, Exceptions, Annotations 
3. Serialization and Deserialization using Jackson-Databind dependency
4. Data Driven testing using JSON file
5. Zip the ExtentReports directory into Project path (you can send this Zip file as well as an Attachment in Email)
6. Automatically open the report after tests execution.
7. Send EMail using Java mail API to User(s) with attachment(s).
------------------------------------------------------------
**How to run the Project from Local machine**
1. Pull the code into your machine and import in IDE (Eclipse/intelliJ).
2. Go to testng_Local.xml -> Run this file as TestNG suite
  It should start the execution -> Parallel Cross Browser Testing.
3. If you want to run it using maven command, then, 
 - mvn clean test
 - mvn clean test -Dbrowser=EDGE -DsuiteFile=testng_Jenkins.xml -DbrowserInstances=5 -Denv=STAGE
 - **NOTE:** stg_config.properties is the default configuration file.
4. To view the Allure reports 
 - Setup the Allure in your machine
 - Go to URL (https://docs.qameta.io/allure/) -> Search for Manual installation -> Steps are mentioned
 - Go to your project location
 - Open command prompt -> allure serve allure-results
------------------------------------------------------------
**How to run the Project from Jenkins**
[Final-Selenium-Github-ActiveChoiceParams.pdf](https://github.com/rajatt95/MasterSeleniumFramework/files/7314832/Final-Selenium-Github-ActiveChoiceParams.pdf)


