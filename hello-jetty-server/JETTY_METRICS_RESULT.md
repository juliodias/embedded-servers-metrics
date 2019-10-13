# Command Used: #
ab -n 15000 -c 15 http://localhost:8081/hello-world

# Results: #
	
~~~~
Server Startup Time:    8.634 seconds
Server Hostname:        localhost
Server Port:            8081

Document Path:          /hello-world
Document Length:        24 bytes

Concurrency Level:      15
Time taken for tests:   8.869 seconds
Complete requests:      15000
Failed requests:        0
Total transferred:      2100000 bytes
HTML transferred:       360000 bytes
Requests per second:    1691.35 [#/sec] (mean)
Time per request:       8.869 [ms] (mean)
Time per request:       0.591 [ms] (mean, across all concurrent requests)
Transfer rate:          231.24 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    2   2.8      1      89
Processing:     0    7   5.5      5     164
Waiting:        0    5   5.0      4     143
Total:          1    9   6.1      7     164

Percentage of the requests served within a certain time (ms)
  50%      7
  66%      9
  75%     10
  80%     11
  90%     14
  95%     16
  98%     22
  99%     29
 100%    164 (longest request)
	
~~~~
