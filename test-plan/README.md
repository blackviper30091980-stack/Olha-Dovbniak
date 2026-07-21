# Test Plan
## Project
Performance Testing of JSONPlaceholder API using Apache JMetre
## Objective
Evaluate the API performance under expected load and identify possible bottlenecks
## Test Environment
- OS: Windows 10
-  Tool: Apache JMetre 5.6.3
-  Protocol: HTTPS
-  Endpoint: https://jsonplaceholder.typicode.com/posts
-  Method: GET
-  ## Test Configuration
-  Number of Threads: 1000
-  Ramp-up Period: 100 seconds
-  Loop Count: 100
-  ## Metrics
-  Avarage Response Time
-  Throughput
-  Error Rate
-  95th Percentile
-  99th Percentile
-  ## Success Criteria
-  Error Rate <1%
-  Avarage Response Time<2 seconds
-  Stable Throughput
-  
-  
