## Command used:
ab -n 15000 -c 15 http://localhost:8080/hello-world

## Result
	
~~~~
Server Startup Time:    9.914
Server Hostname:        localhost
Server Port:            8080

Document Path:          /hello-world
Document Length:        25 bytes

Concurrency Level:      15
Time taken for tests:   10.397 seconds
Complete requests:      15000
Failed requests:        0
Total transferred:      2370000 bytes
HTML transferred:       375000 bytes
Requests per second:    1442.75 [#/sec] (mean)
Time per request:       10.397 [ms] (mean)
Time per request:       0.693 [ms] (mean, across all concurrent requests)
Transfer rate:          222.61 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    2   2.9      1      79
Processing:     1    8   9.2      6     257
Waiting:        0    7   8.3      5     232
Total:          1   10   9.6      8     257

Percentage of the requests served within a certain time (ms)
  50%      8
  66%     10
  75%     11
  80%     12
  90%     16
  95%     22
  98%     32
  99%     49
 100%    257 (longest request)
	
~~~~
