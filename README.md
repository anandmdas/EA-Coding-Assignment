# EA-Coding-Assignment

Project is uploaded as a Zip file

Note: Screenshot of the report is also uploaded outside of the zip file for reference.

Prerequesites to run:
Java
Testng
Maven
IDE
Geckodriver

Scenarios:

Scenario 1: Validate Festival Names displayed in UI is the same as the property file
Description: Iterate through the UI and the Property file(Which contains the list of Festival and Band names) and assert the values in UI and Property file are same for the festival names
 
 Scenario 2: Validate band name under each Festival Names displayed in UI against property file to ensure the band names are mapped to the correct festivals
Description: Iterate through the UI and the Property file(Which contains the list of Festival and Band names) and assert that the band name and festival names are mapped properly

Code Explanation:

Test file is available inside src/main/java/test/SampleTest.java please execute this file to run the script. This file has the above mentioned 2 test scenarios

src/main/java/pages have the methods created inorder to perform the validation of the 2 scenarios
