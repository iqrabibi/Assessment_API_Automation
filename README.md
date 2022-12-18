# Assessment_API_Automation:
This repository contains the API Autoamtion Code

## Technology used:
* Postman
* Newman Reporter
* Node js

## Prerequisites:
* Install Node js
* Install newman using below commands 1) npm install -g newman 2) npm install -g newman-reporter-html

## Execution:

* Clone the project using command git clone https://github.com/iqrabibi/Assessment_API_Automation.git
* Open the terminal where cloned porject is placed.
* Run the command " newman run APIAssessmentTest.postman_collection.json -e QA_Environment.postman_environment.json "
* You can also run the project through postman , just go to postman -> file -> new runner tab -> add collection -> press run button.

## File Description:
APIAssessmentTest.postman_collection.json : this file has all the test cases of APIs along with header , pre req script and assertions.
QA_Environment.postman_environment.json : this file has environmnet related variables and setup

## Sample Execution Images: 


  ![Screenshot_7](https://user-images.githubusercontent.com/19478260/208316969-c188351d-8551-472f-a8c5-76787dccef55.png)
  ![Screenshot_5](https://user-images.githubusercontent.com/19478260/208316976-47670a9e-2d19-4571-bb84-7aa16b3d6adc.png)

