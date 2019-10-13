# Command used: #
ab -n 15000 -c 15 http://localhost:8082/hello-world

# Results: #

Server Startup Time:    9.023 seconds
Server Hostname:        localhost
Server Port:            8082

Document Path:          /hello-world
Document Length:        27 bytes

Concurrency Level:      15
Time taken for tests:   7.864 seconds
Complete requests:      15000
Failed requests:        0
Total transferred:      2430000 bytes
HTML transferred:       405000 bytes
Requests per second:    1907.52 [#/sec] (mean)
Time per request:       7.864 [ms] (mean)
Time per request:       0.524 [ms] (mean, across all concurrent requests)
Transfer rate:          301.78 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    2   2.2      1     141
Processing:     0    6   6.2      4     185
Waiting:        0    4   5.6      3     176
Total:          1    7   6.7      6     186

Percentage of the requests served within a certain time (ms)
  50%      6
  66%      8
  75%      9
  80%     10
  90%     12
  95%     16
  98%     21
  99%     26
 100%    186 (longest request)
