# Performance Testing of [Random User API](https://randomuser.me/api/)

## Project Intro
This project repository's main goals are API performance study and load testing. 
To find the actual TPS (Transaction per second) and discover bottlenecks or stress test points where the system gives 1% error,
we will be load testing the https://randomuser.me/api/ address. For 12 hours, we anticipate a load of 1,20,000 users.

## Tools Used
- Apache JMeter
  
## Steps for setup JMeter
- Download and open [JMeter](https://jmeter.apache.org/download_jmeter.cgi)
- Add thread group with users and time
- Add sampler http request
- Add listeners
- Run thread group

## Expected TPS
- Google spreadsheet : https://docs.google.com/spreadsheets/d/1-cZvtGVerybC-QD16kYMclMq7hQc6HdiCStTERcYXBQ/edit?usp=sharing

### Screenshot:
![excel1](https://github.com/hasan-sagar/Random-User-API-Performance-Test/assets/61242766/975f8c26-24ed-42f5-9eb6-2f6d6ec9574d)

## Bottleneck / Stress test point
- Google spreadsheet : https://docs.google.com/spreadsheets/d/1tBdvuAlIViaHlsKrB1JOUomXlJIRb5EqTtg8BkS7pL0/edit?usp=sharing

### Screenshot:
![excel2](https://github.com/hasan-sagar/Random-User-API-Performance-Test/assets/61242766/cdd98e21-661f-434b-8186-355518691fc0)

### Bottneck Point
![ss2](https://github.com/hasan-sagar/Random-User-API-Performance-Test/assets/61242766/5f6523ea-62de-4b4b-9be6-5f388417fb89)

### Capacity

![ss1](https://github.com/hasan-sagar/Random-User-API-Performance-Test/assets/61242766/969b2247-85f5-4e7b-8beb-f7b38cfd7f84)

### Generated Report

![screencapture-file-F-J-Meter-apache-jmeter-5-6-3-bin-random-user-api-test-Reports-index-html-2024-03-15-15_48_32](https://github.com/hasan-sagar/Random-User-API-Performance-Test/assets/61242766/14aa925a-5b3d-403a-be4c-025009dbd4f2)






