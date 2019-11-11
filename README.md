# PicnicAutomation

### GitHub Gists API
Rest API automation framework implemented using Postman and Newman.

### Prerequisite:
List of all the software and tools required for developing and executing automation framework.

npm (version 5.6.0)
Postman (version 7.9.0)
Newman (version 4.5.5)

### Automation Scripts Execution:
To execute the test script please follow below steps:

1.Download npm from website "https://nodejs.org/en/download/"

2.Install Postman from "https://www.getpostman.com/downloads/"

3.Install Newman inside node modules folder of npm from command line using command "npm install newman –global"

4.Install newman html reporter for better reporting purposes inside node modules folder of npm from command line using command "npm install -g newman-reporter-htmlextra"

5.Download the PicnicTestAutomation.postman_collection.json file

6.Open command line in the directory where this file is stored and run below command: "newman run PicnicTestAutomation.postman_collection.json -r htmlextra --reporter-htmlextra-darkTheme --reporter-htmlextra-title "Picnic Test Automation for Gists""

7.Once the file has run, report will be generated inside a newman folder that would be created in the directory where the json file is saved

### Automation Coverage/Test Scenarios:

As a user, I want to create a public gist.
As a user, I want to see an existing gist.
As a user, I want to edit an existing gist.
As a user, I want to delete an existing gist.
As a user, I want to see a gist that does not exist.
As an unauthorized user, I should not be able to create a gist

### Automation Execution Status:
Newman report is available in the repository "PicnicTestAutomation-2019-11-11-13-40-40-833-0.html" which covers 6 requests with 17 assertions out of which all have PASSED
