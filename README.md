# Random-User-API-Performance-Testing by Jmeter 

## About This Project:
### The Random-User-API Performance Testing project aims to evaluate the Random User Generator API's performance using Apache JMeter. By simulating various load scenarios, this project will identify potential Actual TPS and Bottlenecks/Stress test point. The primary goal of this project is to conduct extensive performance testing on the Random User Generator API using Apache JMeter.

## Tools and Technology:
- Apache Jmeter : The industry-standard tool and an openly available free tool for load testing and performance measurement.

## Server URL:
- Link :  https://random-data-api.com/api/v2/users

## Load Testing: 
### This testing is conducted to evaluate the performance under an intensive and extreme load, the main goal of this testing is to determine the system ability to handle request. In this testing I started with 167 users request in 60 seconds and finally execute with 2834 user request in 1020 seconds and it meets with the expected TPS in every time.
<img width="918" alt="Screenshot for Load test sheet" src="https://github.com/MuksudulIslam/Random-User-API-Performance-Test/assets/143453305/49ff529c-b93e-4e1c-afa6-b5984aa4415c">

## Stress Testing:
### In this Stress tesing I conducted extreme pressure it on and try to find bottleneck or stress test point. Here I check in 1020 seconds try to send 3500, 8000, 12000, 16000 users request and in 16000 user request it show 1% error that is the bottleneck point of this systen.  
<img width="919" alt="Screenshot stress test " src="https://github.com/MuksudulIslam/Random-User-API-Performance-Test/assets/143453305/b24bba5b-276f-4629-ae9c-f630021c9f82">

## How to run this Project:
- Clone this project
- Give following command
- ```sh```
- git clone https://github.com/MuksudulIslam/Random-User-API-Performance-Test

## HTML Reports:
![html report for random api](https://github.com/MuksudulIslam/Random-User-API-Performance-Test/assets/143453305/c00fde22-0c8a-4f6a-aed7-5b5cd999f9e8)





