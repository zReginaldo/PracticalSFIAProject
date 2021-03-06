# Practical-SFIA-Project

## Contents 
* [Project Brief](#ProjectBreif)
* [Introduction](#Introduction) 
* [Planning](#Planning)
* [Use Cases](#UserCases)
* [Risk Analysis](#RiskAssesment) 
* [Front End Design](#Design) 
* [Testing](#Testing)
* [CI Pipeline & Deployment](#Deployment) 
* [Project Conclusion](#Conclusion) 
* [Future Work](#FutureWork) 

<a name="Introduction"></a>
# Introduction 
## Project Brief
* The general outline of this project was to use concepts from previous training modules such as, **Software Development with Python**, **Continuous Integration** and **Cloud Fundamentals** to create a micro-service orientated Flask application. 

* This application had to be composed of at least 4 services that work together, two services that would generate a **random** object, the following service will create another object based on the results of the two services using logic, and lastly the final service will be responsible for communicating with the other 3 services, and also persisting some data in an SQL database. The project required us to deploy this application using Docker and Jenkins. 

### My Solution 
My final solution for the project at hand was to create an application based on the popular TV show COUNTDOWN, where the **Top two** services would produce random numbers and letters, The **Main** service would then take the results, apply logic and post the results to a HTML web page, having the **Final** service take the information posted on to the HTML page and store this into a database.  

<a name="Planning"></a>
## Planning
The best course of action for initiating this project was to set out a plan that would clearly state the duration of time i would have to complete the project, along with the tasks that need to be done so that i stay on track. I decided that using MS Project as my project planning technology was the best course of action. The Gantt chart below neatly displays the project deliverables and timeframe on when to complete each task. 


![Gantt Chart](https://github.com/zReginaldo/PracticalSFIAProject/blob/master/Documentation/Main_Plan.PNG)

<a name="Risk"></a>
## Risk Analysis

![Risk Analysis](https://github.com/zReginaldo/PracticalSFIAProject/blob/master/Documentation/Risk%20Assesment.PNG)


## Project Structure

![Structure](https://github.com/zReginaldo/PracticalSFIAProject/blob/master/Documentation/Project%20Structure.PNG)

## Testing
Testing the Random String Generator Service

![Random String](https://github.com/zReginaldo/PracticalSFIAProject/blob/master/Documentation/RandStr%20Tests.PNG)

Testing the Random Number Generator 

![Random Number](https://github.com/zReginaldo/PracticalSFIAProject/blob/master/Documentation/Testing%20RandNum.PNG)

Testing the Backend Service

![Backend](https://github.com/zReginaldo/PracticalSFIAProject/blob/master/Documentation/Testing%20Backend.PNG)

Test Coverage for entire app 
![Coverage](https://github.com/zReginaldo/PracticalSFIAProject/blob/master/Documentation/Test%20Coverage.PNG)

## Deployment
All services running on docker-compose 

![Coverage](https://github.com/zReginaldo/PracticalSFIAProject/blob/master/Documentation/Docker%20Deployed%20Services.PNG)

The final Application was deployed successfully using Jenkins continuous integration pipeline





