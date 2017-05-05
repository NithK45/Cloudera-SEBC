The full teragen command and job output and The result of the time command
```
[cate@ip-172-31-7-139 ~]$  time hadoop jar /opt/cloudera/parcels/CDH/lib/hadoop-mapreduce/hadoop-mapreduce-examples-2.6.0-cdh5.11.0.jar teragen -Dmapreduce.job.maps=8 -D dfs.block.size=16384 -Dmapreduce.map.memory.mb=536 65536000 /user/cate/tgen
17/05/05 02:00:58 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-7-139.us-west-2.compute.internal/172.31.7.139:8032
17/05/05 02:00:59 INFO terasort.TeraGen: Generating 65536000 using 8
17/05/05 02:00:59 INFO mapreduce.JobSubmitter: number of splits:8
17/05/05 02:00:59 INFO Configuration.deprecation: dfs.block.size is deprecated. Instead, use dfs.blocksize
17/05/05 02:01:00 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1493949234787_0002
17/05/05 02:01:00 INFO impl.YarnClientImpl: Submitted application application_1493949234787_0002
17/05/05 02:01:00 INFO mapreduce.Job: The url to track the job: http://ip-172-31-7-139.us-west-2.compute.internal:8088/proxy/application_1493949234787_0002/
17/05/05 02:01:00 INFO mapreduce.Job: Running job: job_1493949234787_0002
17/05/05 02:01:08 INFO mapreduce.Job: Job job_1493949234787_0002 running in uber mode : false
17/05/05 02:01:08 INFO mapreduce.Job:  map 0% reduce 0%
17/05/05 02:01:28 INFO mapreduce.Job:  map 1% reduce 0%
17/05/05 02:01:36 INFO mapreduce.Job:  map 2% reduce 0%
17/05/05 02:01:46 INFO mapreduce.Job:  map 3% reduce 0%
17/05/05 02:01:52 INFO mapreduce.Job:  map 4% reduce 0%
17/05/05 02:02:00 INFO mapreduce.Job:  map 5% reduce 0%
17/05/05 02:02:10 INFO mapreduce.Job:  map 6% reduce 0%
17/05/05 02:02:16 INFO mapreduce.Job:  map 7% reduce 0%
17/05/05 02:02:22 INFO mapreduce.Job:  map 8% reduce 0%
17/05/05 02:02:29 INFO mapreduce.Job:  map 9% reduce 0%
17/05/05 02:02:35 INFO mapreduce.Job:  map 10% reduce 0%
17/05/05 02:02:41 INFO mapreduce.Job:  map 11% reduce 0%
17/05/05 02:02:47 INFO mapreduce.Job:  map 12% reduce 0%
17/05/05 02:02:55 INFO mapreduce.Job:  map 13% reduce 0%
17/05/05 02:03:01 INFO mapreduce.Job:  map 14% reduce 0%
17/05/05 02:03:07 INFO mapreduce.Job:  map 15% reduce 0%
17/05/05 02:03:16 INFO mapreduce.Job:  map 16% reduce 0%
17/05/05 02:03:22 INFO mapreduce.Job:  map 17% reduce 0%
17/05/05 02:03:28 INFO mapreduce.Job:  map 18% reduce 0%
17/05/05 02:03:34 INFO mapreduce.Job:  map 19% reduce 0%
17/05/05 02:03:40 INFO mapreduce.Job:  map 20% reduce 0%
17/05/05 02:03:46 INFO mapreduce.Job:  map 21% reduce 0%
17/05/05 02:03:53 INFO mapreduce.Job:  map 22% reduce 0%
17/05/05 02:04:01 INFO mapreduce.Job:  map 23% reduce 0%
17/05/05 02:04:07 INFO mapreduce.Job:  map 24% reduce 0%
17/05/05 02:04:13 INFO mapreduce.Job:  map 25% reduce 0%
17/05/05 02:04:19 INFO mapreduce.Job:  map 26% reduce 0%
17/05/05 02:04:25 INFO mapreduce.Job:  map 27% reduce 0%
17/05/05 02:04:31 INFO mapreduce.Job:  map 28% reduce 0%
17/05/05 02:04:37 INFO mapreduce.Job:  map 29% reduce 0%
17/05/05 02:04:43 INFO mapreduce.Job:  map 30% reduce 0%
17/05/05 02:04:52 INFO mapreduce.Job:  map 31% reduce 0%
17/05/05 02:04:58 INFO mapreduce.Job:  map 32% reduce 0%
17/05/05 02:05:05 INFO mapreduce.Job:  map 33% reduce 0%
17/05/05 02:05:12 INFO mapreduce.Job:  map 34% reduce 0%
17/05/05 02:05:18 INFO mapreduce.Job:  map 35% reduce 0%
17/05/05 02:05:24 INFO mapreduce.Job:  map 36% reduce 0%
17/05/05 02:05:30 INFO mapreduce.Job:  map 37% reduce 0%
17/05/05 02:05:36 INFO mapreduce.Job:  map 38% reduce 0%
17/05/05 02:05:42 INFO mapreduce.Job:  map 39% reduce 0%
17/05/05 02:05:48 INFO mapreduce.Job:  map 40% reduce 0%
17/05/05 02:05:54 INFO mapreduce.Job:  map 41% reduce 0%
17/05/05 02:06:01 INFO mapreduce.Job:  map 42% reduce 0%
17/05/05 02:06:07 INFO mapreduce.Job:  map 43% reduce 0%
17/05/05 02:06:14 INFO mapreduce.Job:  map 44% reduce 0%
17/05/05 02:06:19 INFO mapreduce.Job:  map 45% reduce 0%
17/05/05 02:06:26 INFO mapreduce.Job:  map 46% reduce 0%
17/05/05 02:06:31 INFO mapreduce.Job:  map 47% reduce 0%
17/05/05 02:06:37 INFO mapreduce.Job:  map 48% reduce 0%
17/05/05 02:06:44 INFO mapreduce.Job:  map 49% reduce 0%
17/05/05 02:06:50 INFO mapreduce.Job:  map 50% reduce 0%
17/05/05 02:06:59 INFO mapreduce.Job:  map 51% reduce 0%
17/05/05 02:07:05 INFO mapreduce.Job:  map 52% reduce 0%
17/05/05 02:07:11 INFO mapreduce.Job:  map 53% reduce 0%
17/05/05 02:07:17 INFO mapreduce.Job:  map 54% reduce 0%
17/05/05 02:07:23 INFO mapreduce.Job:  map 55% reduce 0%
17/05/05 02:07:29 INFO mapreduce.Job:  map 56% reduce 0%
17/05/05 02:07:35 INFO mapreduce.Job:  map 57% reduce 0%
17/05/05 02:07:41 INFO mapreduce.Job:  map 58% reduce 0%
17/05/05 02:07:47 INFO mapreduce.Job:  map 59% reduce 0%
17/05/05 02:07:56 INFO mapreduce.Job:  map 60% reduce 0%
17/05/05 02:08:03 INFO mapreduce.Job:  map 61% reduce 0%
17/05/05 02:08:09 INFO mapreduce.Job:  map 62% reduce 0%
17/05/05 02:08:15 INFO mapreduce.Job:  map 63% reduce 0%
17/05/05 02:08:21 INFO mapreduce.Job:  map 64% reduce 0%
17/05/05 02:08:27 INFO mapreduce.Job:  map 65% reduce 0%
17/05/05 02:08:33 INFO mapreduce.Job:  map 66% reduce 0%
17/05/05 02:08:39 INFO mapreduce.Job:  map 67% reduce 0%
17/05/05 02:08:45 INFO mapreduce.Job:  map 68% reduce 0%
17/05/05 02:08:53 INFO mapreduce.Job:  map 69% reduce 0%
17/05/05 02:09:00 INFO mapreduce.Job:  map 70% reduce 0%
17/05/05 02:09:06 INFO mapreduce.Job:  map 71% reduce 0%
17/05/05 02:09:12 INFO mapreduce.Job:  map 72% reduce 0%
17/05/05 02:09:18 INFO mapreduce.Job:  map 73% reduce 0%
17/05/05 02:09:24 INFO mapreduce.Job:  map 74% reduce 0%
17/05/05 02:09:30 INFO mapreduce.Job:  map 75% reduce 0%
17/05/05 02:09:36 INFO mapreduce.Job:  map 76% reduce 0%
17/05/05 02:09:42 INFO mapreduce.Job:  map 77% reduce 0%
17/05/05 02:09:48 INFO mapreduce.Job:  map 78% reduce 0%
17/05/05 02:09:56 INFO mapreduce.Job:  map 79% reduce 0%
17/05/05 02:10:02 INFO mapreduce.Job:  map 80% reduce 0%
17/05/05 02:10:08 INFO mapreduce.Job:  map 81% reduce 0%
17/05/05 02:10:14 INFO mapreduce.Job:  map 82% reduce 0%
17/05/05 02:10:20 INFO mapreduce.Job:  map 83% reduce 0%
17/05/05 02:10:26 INFO mapreduce.Job:  map 84% reduce 0%
17/05/05 02:10:35 INFO mapreduce.Job:  map 85% reduce 0%
17/05/05 02:10:41 INFO mapreduce.Job:  map 86% reduce 0%
17/05/05 02:10:48 INFO mapreduce.Job:  map 87% reduce 0%
17/05/05 02:10:57 INFO mapreduce.Job:  map 88% reduce 0%
17/05/05 02:11:03 INFO mapreduce.Job:  map 89% reduce 0%
17/05/05 02:11:09 INFO mapreduce.Job:  map 90% reduce 0%
17/05/05 02:11:18 INFO mapreduce.Job:  map 91% reduce 0%
17/05/05 02:11:24 INFO mapreduce.Job:  map 92% reduce 0%
17/05/05 02:11:30 INFO mapreduce.Job:  map 93% reduce 0%
17/05/05 02:11:36 INFO mapreduce.Job:  map 94% reduce 0%
17/05/05 02:11:42 INFO mapreduce.Job:  map 95% reduce 0%
17/05/05 02:11:48 INFO mapreduce.Job:  map 96% reduce 0%
17/05/05 02:11:55 INFO mapreduce.Job:  map 97% reduce 0%
17/05/05 02:12:03 INFO mapreduce.Job:  map 98% reduce 0%
17/05/05 02:12:09 INFO mapreduce.Job:  map 99% reduce 0%
17/05/05 02:12:15 INFO mapreduce.Job:  map 100% reduce 0%
17/05/05 02:12:20 INFO mapreduce.Job: Job job_1493949234787_0002 completed successfully
17/05/05 02:12:20 INFO mapreduce.Job: Counters: 33
        File System Counters
                FILE: Number of bytes read=0
                FILE: Number of bytes written=1020832
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=682
                HDFS: Number of bytes written=6553600000
                HDFS: Number of read operations=32
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=16
        Job Counters
                Launched map tasks=8
                Other local map tasks=8
                Total time spent by all maps in occupied slots (ms)=5320850
                Total time spent by all reduces in occupied slots (ms)=0
                Total time spent by all map tasks (ms)=5320850
                Total vcore-milliseconds taken by all map tasks=5320850
                Total megabyte-milliseconds taken by all map tasks=5448550400
        Map-Reduce Framework
                Map input records=65536000
                Map output records=65536000
                Input split bytes=682
                Spilled Records=0
                Failed Shuffles=0
                Merged Map outputs=0
                GC time elapsed (ms)=5657
                CPU time spent (ms)=836230
                Physical memory (bytes) snapshot=1163292672
                Virtual memory (bytes) snapshot=9145077760
                Total committed heap usage (bytes)=1564475392
                Peak Map Physical memory (bytes)=253968384
                Peak Map Virtual memory (bytes)=1151684608
        org.apache.hadoop.examples.terasort.TeraGen$Counters
                CHECKSUM=140750829423462787
        File Input Format Counters
                Bytes Read=0
        File Output Format Counters
                Bytes Written=6553600000

real    11m25.201s
user    0m8.511s
sys     0m1.268s
[cate@ip-172-31-7-139 ~]$
```
The command and output of hdfs dfs -ls /user/cate/tgen
```
[cate@ip-172-31-7-139 ~]$ hdfs dfs -ls /user/cate/tgen
Found 9 items
-rw-r--r--   3 cate aussies          0 2017-05-05 02:12 /user/cate/tgen/_SUCCESS
-rw-r--r--   3 cate aussies  819200000 2017-05-05 02:12 /user/cate/tgen/part-m-00000
-rw-r--r--   3 cate aussies  819200000 2017-05-05 02:12 /user/cate/tgen/part-m-00001
-rw-r--r--   3 cate aussies  819200000 2017-05-05 02:12 /user/cate/tgen/part-m-00002
-rw-r--r--   3 cate aussies  819200000 2017-05-05 02:12 /user/cate/tgen/part-m-00003
-rw-r--r--   3 cate aussies  819200000 2017-05-05 02:12 /user/cate/tgen/part-m-00004
-rw-r--r--   3 cate aussies  819200000 2017-05-05 02:12 /user/cate/tgen/part-m-00005
-rw-r--r--   3 cate aussies  819200000 2017-05-05 02:12 /user/cate/tgen/part-m-00006
-rw-r--r--   3 cate aussies  819200000 2017-05-05 02:12 /user/cate/tgen/part-m-00007

```