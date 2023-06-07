# Random-User-API-Performance-Test

## Steps:
- Created a jmx file for load testing of a public API named Random-User-API
- Generated the report of Load testing and stress testing in Excel format with the actual and expected TPS
- The test result screenshots are added in the word file

## Technology Used
- JMeter
- Jdk-11

## Scenerio
Find out the actual TPS for if 120000 user can give load for 12 hour
Perform load test on this URL: https://random-data-api.com/api/v2/users
1. You have to find out if the expected TPS (Transaction Per/Second) meet the above requirement.
Breakdown the expected TPS in excel sheet and find out the actual TPS
2. Create another excel sheet where you will try to find out the bottleneck/stress test point. (At which point the system starts to show 1% error)

## How to run this project
- Clone this project
- Save the .jmx file in bin folder of Apche Jmeter
- Run the .jmx file on jmeter

**The TPS and test breakdown report screenshot is added below:**

*Load testing:

![Load](https://github.com/suptimusfika/Random-User-API-Performance-Test/assets/48064134/fa80178f-d105-434c-a442-69fbd3cd6e16)

*Stress testing:
![stress](https://github.com/suptimusfika/Random-User-API-Performance-Test/assets/48064134/cec5cd20-4167-4958-9eec-6a05613d7395)

**Individual test breakdown screenshots are added below:**

*For 60s and 167 users:
![Screenshot (1014)](https://github.com/suptimusfika/Random-User-API-Performance-Test/assets/48064134/67f10b80-c09a-46e8-a572-862e33cf936f)

  
*For 300s and 833 users:
![Screenshot (1017)](https://github.com/suptimusfika/Random-User-API-Performance-Test/assets/48064134/a1f266ba-488a-449a-ae59-472e13988969)


*For 600s and 1667 users:
![Screenshot (1018)](https://github.com/suptimusfika/Random-User-API-Performance-Test/assets/48064134/c2a27300-38c4-424c-aabb-3d2fe965fb59)


  
*For 900s and 2500 users:
![Screenshot (1019)](https://github.com/suptimusfika/Random-User-API-Performance-Test/assets/48064134/ca8fa8d6-b1bf-4921-a21d-da03e6dacc6c)

*For 1800s and 5000 users(HTML Report)
![Apache-JMeter-Dashboard (1)](https://github.com/suptimusfika/Random-User-API-Performance-Test/assets/48064134/f6c2607e-4602-4517-9185-e0f92731cd46)

  
