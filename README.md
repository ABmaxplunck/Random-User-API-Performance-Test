# Random-User-API-Performance-Test

## Project Scenario: 
Find out the actual TPS for if 120000 users can give load for 12 hours Perform load test on this URL: https://random-data-api.com/api/v2/users

## Tools & Technology used: Apache JMeter

* Open source application – Apache JMeter is a freely accessible tool that enables users or developers to utilize its code for various development or customization purposes
* Platform independent – It has cross-platform compatibility and the capability to assess the load and performance of server requests on various systems
* User friendly GUI – It's straightforward, uncomplicated, and easy to grasp
* Setting up – Installing it on various operating systems is straightforward
* Record & Run: JMeter provides the facility to record the steps by using Blaze master add-on & run with any number of threads & listeners.

## Server URL:
* Perform load test on this URL.
* Link: https://random-data-api.com/api/v2/users

## Jmeter Performance Testing Image
* I have conducted performance testing, which encompassed Load Testing and Stress Testing
* Load Testing: This testing is used to check the extreme load of a system that can be aimed to handle. I started with 834 requests in 300 seconds and finally I executed with 4167 requests in 1500 seconds. I 
  got the expected TPS (2.7) for every test iteration.

  ![pic 1](https://github.com/ABmaxplunck/Random-User-API-Performance-Test/assets/51376551/5fc3e261-4ff6-4006-ad7e-3d3bec704eb4)



* Stress Test: This test tries to break the system by crushing its resources. I checked it in 25 minutes (1500 seconds) considreing 3334, 3500, 4000, 5000 requests. This server successfully run with these requests except 5000 requests in 1500 seconds. It shows an error 1% that is called as bottleneck point.
  
![pic 2](https://github.com/ABmaxplunck/Random-User-API-Performance-Test/assets/51376551/3bbe2cc0-f892-48b6-8e52-c06e1bc96dd4)


## Google Drive Link:
* Random-User-API-Performance-Test Image Drive link: https://shorturl.at/kFW08


