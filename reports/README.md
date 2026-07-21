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
- ### Graph Analisys
- RESPONSE TIME OVER TIME:- respons time remained generally stable during the test;
- only a few spikes inthe middle of the test were observed;
- avarage response time is 1412ms
- TRANSACTIONS PER SECOND:-throughput remained stable;
- avarage throughput is 159,1 request per second;
- transaction rate during almost 4 min was high (400-450 ), then it dropped to 100-50 as almost all the virtual users had proceded their iterations
- ACTIVE THREADS:the number of active virtual users increased fastly according to the ramp-up settings,after that it gradually was decreasing as the virtual users had gradually proceded ther scenarios and logged out 
- 
- ## Conclusion
- The server remaind stable during the test.Almost all requests were processed successfully.The response time was generally acceptable,the high standart deviation indicates noticeablevariation in response times under load.The API successfully handled the configured load.The error rate was only 0.02%,throughput remained stable,and no critical performance degradation was observed.Overall,the system demonstrated acceptable performance under the tested load.
- 
