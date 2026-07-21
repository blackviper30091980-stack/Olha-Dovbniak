# Load Testing Report
## Summary
The Load test was executed using Apache JMetre
### Test Configurations 
- Threads: 1000
- Ramp-up : 100 seconds
- Loop Count: 100
### Results
- Avarage Response Time:1412ms
- 95 Percentile:3103ms
- 99 Persentile:16299ms
- Throughput:159,1/sec
- Error Rate:0,02%
- Standart Deviation: 9336,54
- Test Duration:10m 20sec
- ## Conclusion
- The server remaind stable during the test.Almost all requests were processed successfully.The response time was generally acceptable,the high standart deviation indicates noticeablevariation in response times under load.
- 
