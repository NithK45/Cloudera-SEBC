
Teragen full command
```
time hadoop jar /opt/cloudera/parcels/CDH/lib/hadoop-mapreduce/hadoop-mapreduce-examples-2.6.0-cdh5.9.2.jar teragen -Dmapreduce.job.maps=4 -D dfs.block.size=33554432 100000000 /user/NithK45/teragen.out
```
Teragen command output (time at the end of the output)

```
[NithK45@ip-172-31-38-19 ~]$ time hadoop jar /opt/cloudera/parcels/CDH/lib/hadoop-mapreduce/hadoop-mapreduce-examples-2.6.0-cdh5.9.2.jar teragen -Dmapreduce.job.maps=4 -D dfs.block.size=33554432 100000000 /user/NithK45/teragen.out
17/05/03 01:34:47 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-38-19.us-west-2.compute.internal/172.31.38.19:8032
17/05/03 01:34:48 INFO terasort.TeraSort: Generating 100000000 using 4
17/05/03 01:34:48 INFO mapreduce.JobSubmitter: number of splits:4
17/05/03 01:34:48 INFO Configuration.deprecation: dfs.block.size is deprecated. Instead, use dfs.blocksize
17/05/03 01:34:48 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1493768809355_0002
17/05/03 01:34:48 INFO impl.YarnClientImpl: Submitted application application_1493768809355_0002
17/05/03 01:34:48 INFO mapreduce.Job: The url to track the job: http://ip-172-31-38-19.us-west-2.compute.internal:8088/proxy/application_1493768809355_0002/
17/05/03 01:34:48 INFO mapreduce.Job: Running job: job_1493768809355_0002
17/05/03 01:34:57 INFO mapreduce.Job: Job job_1493768809355_0002 running in uber mode : false
17/05/03 01:34:57 INFO mapreduce.Job:  map 0% reduce 0%
17/05/03 01:35:09 INFO mapreduce.Job:  map 4% reduce 0%
17/05/03 01:35:10 INFO mapreduce.Job:  map 8% reduce 0%
17/05/03 01:35:12 INFO mapreduce.Job:  map 9% reduce 0%
17/05/03 01:35:13 INFO mapreduce.Job:  map 11% reduce 0%
17/05/03 01:35:15 INFO mapreduce.Job:  map 12% reduce 0%
17/05/03 01:35:16 INFO mapreduce.Job:  map 15% reduce 0%
17/05/03 01:35:19 INFO mapreduce.Job:  map 17% reduce 0%
17/05/03 01:35:22 INFO mapreduce.Job:  map 19% reduce 0%
17/05/03 01:35:24 INFO mapreduce.Job:  map 20% reduce 0%
17/05/03 01:35:25 INFO mapreduce.Job:  map 21% reduce 0%
17/05/03 01:35:27 INFO mapreduce.Job:  map 23% reduce 0%
17/05/03 01:35:30 INFO mapreduce.Job:  map 25% reduce 0%
17/05/03 01:35:33 INFO mapreduce.Job:  map 26% reduce 0%
17/05/03 01:35:34 INFO mapreduce.Job:  map 28% reduce 0%
17/05/03 01:35:36 INFO mapreduce.Job:  map 30% reduce 0%
17/05/03 01:35:39 INFO mapreduce.Job:  map 31% reduce 0%
17/05/03 01:35:40 INFO mapreduce.Job:  map 32% reduce 0%
17/05/03 01:35:42 INFO mapreduce.Job:  map 33% reduce 0%
17/05/03 01:35:43 INFO mapreduce.Job:  map 34% reduce 0%
17/05/03 01:35:45 INFO mapreduce.Job:  map 35% reduce 0%
17/05/03 01:35:46 INFO mapreduce.Job:  map 36% reduce 0%
17/05/03 01:35:48 INFO mapreduce.Job:  map 37% reduce 0%
17/05/03 01:35:49 INFO mapreduce.Job:  map 39% reduce 0%
17/05/03 01:35:51 INFO mapreduce.Job:  map 40% reduce 0%
17/05/03 01:35:54 INFO mapreduce.Job:  map 43% reduce 0%
17/05/03 01:35:57 INFO mapreduce.Job:  map 45% reduce 0%
17/05/03 01:36:00 INFO mapreduce.Job:  map 47% reduce 0%
17/05/03 01:36:03 INFO mapreduce.Job:  map 49% reduce 0%
17/05/03 01:36:07 INFO mapreduce.Job:  map 51% reduce 0%
17/05/03 01:36:10 INFO mapreduce.Job:  map 53% reduce 0%
17/05/03 01:36:13 INFO mapreduce.Job:  map 55% reduce 0%
17/05/03 01:36:16 INFO mapreduce.Job:  map 57% reduce 0%
17/05/03 01:36:19 INFO mapreduce.Job:  map 59% reduce 0%
17/05/03 01:36:22 INFO mapreduce.Job:  map 61% reduce 0%
17/05/03 01:36:25 INFO mapreduce.Job:  map 63% reduce 0%
17/05/03 01:36:28 INFO mapreduce.Job:  map 65% reduce 0%
17/05/03 01:36:31 INFO mapreduce.Job:  map 67% reduce 0%
17/05/03 01:36:34 INFO mapreduce.Job:  map 69% reduce 0%
17/05/03 01:36:37 INFO mapreduce.Job:  map 71% reduce 0%
17/05/03 01:36:40 INFO mapreduce.Job:  map 73% reduce 0%
17/05/03 01:36:43 INFO mapreduce.Job:  map 75% reduce 0%
17/05/03 01:36:46 INFO mapreduce.Job:  map 77% reduce 0%
17/05/03 01:36:48 INFO mapreduce.Job:  map 78% reduce 0%
17/05/03 01:36:49 INFO mapreduce.Job:  map 80% reduce 0%
17/05/03 01:36:52 INFO mapreduce.Job:  map 82% reduce 0%
17/05/03 01:36:54 INFO mapreduce.Job:  map 83% reduce 0%
17/05/03 01:36:55 INFO mapreduce.Job:  map 84% reduce 0%
17/05/03 01:36:58 INFO mapreduce.Job:  map 86% reduce 0%
17/05/03 01:37:02 INFO mapreduce.Job:  map 88% reduce 0%
17/05/03 01:37:05 INFO mapreduce.Job:  map 90% reduce 0%
17/05/03 01:37:08 INFO mapreduce.Job:  map 92% reduce 0%
17/05/03 01:37:11 INFO mapreduce.Job:  map 93% reduce 0%
17/05/03 01:37:13 INFO mapreduce.Job:  map 94% reduce 0%
17/05/03 01:37:14 INFO mapreduce.Job:  map 96% reduce 0%
17/05/03 01:37:17 INFO mapreduce.Job:  map 98% reduce 0%
17/05/03 01:37:19 INFO mapreduce.Job:  map 99% reduce 0%
17/05/03 01:37:20 INFO mapreduce.Job:  map 100% reduce 0%
17/05/03 01:37:21 INFO mapreduce.Job: Job job_1493768809355_0002 completed successfully
17/05/03 01:37:21 INFO mapreduce.Job: Counters: 31
        File System Counters
                FILE: Number of bytes read=0
                FILE: Number of bytes written=494140
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=344
                HDFS: Number of bytes written=10000000000
                HDFS: Number of read operations=16
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=8
        Job Counters
                Launched map tasks=4
                Other local map tasks=4
                Total time spent by all maps in occupied slots (ms)=563667
                Total time spent by all reduces in occupied slots (ms)=0
                Total time spent by all map tasks (ms)=563667
                Total vcore-seconds taken by all map tasks=563667
                Total megabyte-seconds taken by all map tasks=577195008
        Map-Reduce Framework
                Map input records=100000000
                Map output records=100000000
                Input split bytes=344
                Spilled Records=0
                Failed Shuffles=0
                Merged Map outputs=0
                GC time elapsed (ms)=1518
                CPU time spent (ms)=154560
                Physical memory (bytes) snapshot=1078218752
                Virtual memory (bytes) snapshot=6251761664
                Total committed heap usage (bytes)=863502336
        org.apache.hadoop.examples.terasort.TeraGen$Counters
                CHECKSUM=214760662691937609
        File Input Format Counters
                Bytes Read=0
        File Output Format Counters
                Bytes Written=10000000000

real    2m36.725s
user    0m6.217s
sys     0m0.785s
```

2. Terasort command

```
time hadoop jar /opt/cloudera/parcels/CDH-5.9.2-1.cdh5.9.2.p0.3/lib/hadoop-mapreduce/hadoop-mapreduce-examples-2.6.0-cdh5.9.2.jar terasort /user/NithK45/teragen.out /user/NithK45/terasort.out
```

Terasort full output (time at the end of the output)

```
[hdfs@ip-172-31-38-19 ~]$ time hadoop jar /opt/cloudera/parcels/CDH-5.9.2-1.cdh5.9.2.p0.3/lib/hadoop-mapreduce/hadoop-mapreduce-examples-2.6.0-cdh5.9.2.jar terasort /user/NithK45/teragen.out /user/NithK45/terasort.out
17/05/03 04:46:45 INFO terasort.TeraSort: starting
17/05/03 04:46:47 INFO input.FileInputFormat: Total input paths to process : 4
Spent 343ms computing base-splits.
Spent 6ms computing TeraScheduler splits.
Computing input splits took 350ms
Sampling 10 splits of 300
Making 6 from 100000 sampled records
Computing parititions took 1533ms
Spent 1887ms computing partitions.
17/05/03 04:46:49 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-38-19.us-west-2.compute.internal/172.31.38.19:8032
17/05/03 04:46:49 INFO mapreduce.JobSubmitter: number of splits:300
17/05/03 04:46:49 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1493779454395_0003
17/05/03 04:46:50 INFO impl.YarnClientImpl: Submitted application application_1493779454395_0003
17/05/03 04:46:50 INFO mapreduce.Job: The url to track the job: http://ip-172-31-38-19.us-west-2.compute.internal:8088/proxy/application_1493779454395_0003/
17/05/03 04:46:50 INFO mapreduce.Job: Running job: job_1493779454395_0003
17/05/03 04:46:57 INFO mapreduce.Job: Job job_1493779454395_0003 running in uber mode : false
17/05/03 04:46:57 INFO mapreduce.Job:  map 0% reduce 0%
17/05/03 04:47:09 INFO mapreduce.Job:  map 1% reduce 0%
17/05/03 04:47:12 INFO mapreduce.Job:  map 3% reduce 0%
17/05/03 04:47:13 INFO mapreduce.Job:  map 4% reduce 0%
17/05/03 04:47:20 INFO mapreduce.Job:  map 5% reduce 0%
17/05/03 04:47:25 INFO mapreduce.Job:  map 6% reduce 0%
17/05/03 04:47:27 INFO mapreduce.Job:  map 7% reduce 0%
17/05/03 04:47:29 INFO mapreduce.Job:  map 8% reduce 0%
17/05/03 04:47:38 INFO mapreduce.Job:  map 9% reduce 0%
17/05/03 04:47:39 INFO mapreduce.Job:  map 10% reduce 0%
17/05/03 04:47:40 INFO mapreduce.Job:  map 11% reduce 0%
17/05/03 04:47:41 INFO mapreduce.Job:  map 12% reduce 0%
17/05/03 04:47:50 INFO mapreduce.Job:  map 13% reduce 0%
17/05/03 04:47:52 INFO mapreduce.Job:  map 14% reduce 0%
17/05/03 04:47:55 INFO mapreduce.Job:  map 16% reduce 0%
17/05/03 04:48:00 INFO mapreduce.Job:  map 17% reduce 0%
17/05/03 04:48:06 INFO mapreduce.Job:  map 18% reduce 0%
17/05/03 04:48:10 INFO mapreduce.Job:  map 20% reduce 0%
17/05/03 04:48:18 INFO mapreduce.Job:  map 21% reduce 0%
17/05/03 04:48:20 INFO mapreduce.Job:  map 22% reduce 0%
17/05/03 04:48:21 INFO mapreduce.Job:  map 23% reduce 0%
17/05/03 04:48:25 INFO mapreduce.Job:  map 24% reduce 0%
17/05/03 04:48:31 INFO mapreduce.Job:  map 25% reduce 0%
17/05/03 04:48:32 INFO mapreduce.Job:  map 26% reduce 0%
17/05/03 04:48:38 INFO mapreduce.Job:  map 27% reduce 0%
17/05/03 04:48:39 INFO mapreduce.Job:  map 28% reduce 0%
17/05/03 04:48:41 INFO mapreduce.Job:  map 29% reduce 0%
17/05/03 04:48:46 INFO mapreduce.Job:  map 30% reduce 0%
17/05/03 04:48:50 INFO mapreduce.Job:  map 31% reduce 0%
17/05/03 04:48:53 INFO mapreduce.Job:  map 32% reduce 0%
17/05/03 04:48:57 INFO mapreduce.Job:  map 33% reduce 0%
17/05/03 04:49:00 INFO mapreduce.Job:  map 34% reduce 0%
17/05/03 04:49:01 INFO mapreduce.Job:  map 35% reduce 0%
17/05/03 04:49:07 INFO mapreduce.Job:  map 36% reduce 0%
17/05/03 04:49:10 INFO mapreduce.Job:  map 37% reduce 0%
17/05/03 04:49:12 INFO mapreduce.Job:  map 38% reduce 0%
17/05/03 04:49:19 INFO mapreduce.Job:  map 39% reduce 0%
17/05/03 04:49:21 INFO mapreduce.Job:  map 40% reduce 0%
17/05/03 04:49:22 INFO mapreduce.Job:  map 41% reduce 0%
17/05/03 04:49:25 INFO mapreduce.Job:  map 42% reduce 0%
17/05/03 04:49:32 INFO mapreduce.Job:  map 43% reduce 0%
17/05/03 04:49:34 INFO mapreduce.Job:  map 44% reduce 0%
17/05/03 04:49:36 INFO mapreduce.Job:  map 45% reduce 0%
17/05/03 04:49:38 INFO mapreduce.Job:  map 46% reduce 0%
17/05/03 04:49:41 INFO mapreduce.Job:  map 47% reduce 0%
17/05/03 04:49:49 INFO mapreduce.Job:  map 49% reduce 0%
17/05/03 04:49:51 INFO mapreduce.Job:  map 50% reduce 0%
17/05/03 04:49:59 INFO mapreduce.Job:  map 51% reduce 0%
17/05/03 04:50:02 INFO mapreduce.Job:  map 52% reduce 0%
17/05/03 04:50:03 INFO mapreduce.Job:  map 53% reduce 0%
17/05/03 04:50:05 INFO mapreduce.Job:  map 54% reduce 0%
17/05/03 04:50:11 INFO mapreduce.Job:  map 55% reduce 0%
17/05/03 04:50:16 INFO mapreduce.Job:  map 56% reduce 0%
17/05/03 04:50:17 INFO mapreduce.Job:  map 57% reduce 0%
17/05/03 04:50:18 INFO mapreduce.Job:  map 58% reduce 0%
17/05/03 04:50:22 INFO mapreduce.Job:  map 59% reduce 0%
17/05/03 04:50:30 INFO mapreduce.Job:  map 60% reduce 0%
17/05/03 04:50:31 INFO mapreduce.Job:  map 62% reduce 0%
17/05/03 04:50:37 INFO mapreduce.Job:  map 63% reduce 0%
17/05/03 04:50:42 INFO mapreduce.Job:  map 64% reduce 0%
17/05/03 04:50:44 INFO mapreduce.Job:  map 66% reduce 0%
17/05/03 04:50:50 INFO mapreduce.Job:  map 67% reduce 0%
17/05/03 04:50:55 INFO mapreduce.Job:  map 68% reduce 0%
17/05/03 04:50:57 INFO mapreduce.Job:  map 69% reduce 0%
17/05/03 04:50:58 INFO mapreduce.Job:  map 70% reduce 0%
17/05/03 04:51:02 INFO mapreduce.Job:  map 71% reduce 0%
17/05/03 04:51:09 INFO mapreduce.Job:  map 72% reduce 0%
17/05/03 04:51:11 INFO mapreduce.Job:  map 73% reduce 0%
17/05/03 04:51:14 INFO mapreduce.Job:  map 74% reduce 0%
17/05/03 04:51:15 INFO mapreduce.Job:  map 75% reduce 0%
17/05/03 04:51:21 INFO mapreduce.Job:  map 76% reduce 0%
17/05/03 04:51:24 INFO mapreduce.Job:  map 77% reduce 0%
17/05/03 04:51:27 INFO mapreduce.Job:  map 78% reduce 0%
17/05/03 04:51:31 INFO mapreduce.Job:  map 79% reduce 0%
17/05/03 04:51:32 INFO mapreduce.Job:  map 80% reduce 0%
17/05/03 04:51:37 INFO mapreduce.Job:  map 81% reduce 0%
17/05/03 04:51:41 INFO mapreduce.Job:  map 82% reduce 0%
17/05/03 04:51:42 INFO mapreduce.Job:  map 83% reduce 0%
17/05/03 04:51:45 INFO mapreduce.Job:  map 84% reduce 0%
17/05/03 04:51:52 INFO mapreduce.Job:  map 84% reduce 2%
17/05/03 04:51:54 INFO mapreduce.Job:  map 85% reduce 2%
17/05/03 04:51:55 INFO mapreduce.Job:  map 85% reduce 3%
17/05/03 04:51:56 INFO mapreduce.Job:  map 85% reduce 4%
17/05/03 04:51:57 INFO mapreduce.Job:  map 85% reduce 9%
17/05/03 04:51:58 INFO mapreduce.Job:  map 85% reduce 10%
17/05/03 04:51:59 INFO mapreduce.Job:  map 86% reduce 11%
17/05/03 04:52:03 INFO mapreduce.Job:  map 86% reduce 14%
17/05/03 04:52:04 INFO mapreduce.Job:  map 87% reduce 16%
17/05/03 04:52:06 INFO mapreduce.Job:  map 87% reduce 17%
17/05/03 04:52:09 INFO mapreduce.Job:  map 87% reduce 18%
17/05/03 04:52:10 INFO mapreduce.Job:  map 87% reduce 20%
17/05/03 04:52:11 INFO mapreduce.Job:  map 87% reduce 21%
17/05/03 04:52:12 INFO mapreduce.Job:  map 88% reduce 21%
17/05/03 04:52:13 INFO mapreduce.Job:  map 88% reduce 22%
17/05/03 04:52:15 INFO mapreduce.Job:  map 89% reduce 22%
17/05/03 04:52:16 INFO mapreduce.Job:  map 89% reduce 24%
17/05/03 04:52:19 INFO mapreduce.Job:  map 89% reduce 25%
17/05/03 04:52:23 INFO mapreduce.Job:  map 90% reduce 25%
17/05/03 04:52:25 INFO mapreduce.Job:  map 91% reduce 25%
17/05/03 04:52:30 INFO mapreduce.Job:  map 92% reduce 25%
17/05/03 04:52:35 INFO mapreduce.Job:  map 93% reduce 26%
17/05/03 04:52:37 INFO mapreduce.Job:  map 94% reduce 26%
17/05/03 04:52:45 INFO mapreduce.Job:  map 95% reduce 26%
17/05/03 04:52:46 INFO mapreduce.Job:  map 96% reduce 26%
17/05/03 04:52:47 INFO mapreduce.Job:  map 96% reduce 27%
17/05/03 04:52:53 INFO mapreduce.Job:  map 97% reduce 27%
17/05/03 04:52:56 INFO mapreduce.Job:  map 98% reduce 27%
17/05/03 04:53:01 INFO mapreduce.Job:  map 99% reduce 27%
17/05/03 04:53:06 INFO mapreduce.Job:  map 100% reduce 27%
17/05/03 04:53:07 INFO mapreduce.Job:  map 100% reduce 28%
17/05/03 04:53:08 INFO mapreduce.Job:  map 100% reduce 32%
17/05/03 04:53:09 INFO mapreduce.Job:  map 100% reduce 37%
17/05/03 04:53:10 INFO mapreduce.Job:  map 100% reduce 49%
17/05/03 04:53:11 INFO mapreduce.Job:  map 100% reduce 56%
17/05/03 04:53:12 INFO mapreduce.Job:  map 100% reduce 58%
17/05/03 04:53:13 INFO mapreduce.Job:  map 100% reduce 60%
17/05/03 04:53:14 INFO mapreduce.Job:  map 100% reduce 61%
17/05/03 04:53:15 INFO mapreduce.Job:  map 100% reduce 62%
17/05/03 04:53:16 INFO mapreduce.Job:  map 100% reduce 63%
17/05/03 04:53:17 INFO mapreduce.Job:  map 100% reduce 64%
17/05/03 04:53:18 INFO mapreduce.Job:  map 100% reduce 65%
17/05/03 04:53:19 INFO mapreduce.Job:  map 100% reduce 67%
17/05/03 04:53:20 INFO mapreduce.Job:  map 100% reduce 68%
17/05/03 04:53:21 INFO mapreduce.Job:  map 100% reduce 69%
17/05/03 04:53:22 INFO mapreduce.Job:  map 100% reduce 70%
17/05/03 04:53:23 INFO mapreduce.Job:  map 100% reduce 72%
17/05/03 04:53:24 INFO mapreduce.Job:  map 100% reduce 73%
17/05/03 04:53:25 INFO mapreduce.Job:  map 100% reduce 74%
17/05/03 04:53:26 INFO mapreduce.Job:  map 100% reduce 80%
17/05/03 04:53:27 INFO mapreduce.Job:  map 100% reduce 81%
17/05/03 04:53:28 INFO mapreduce.Job:  map 100% reduce 82%
17/05/03 04:53:29 INFO mapreduce.Job:  map 100% reduce 84%
17/05/03 04:53:31 INFO mapreduce.Job:  map 100% reduce 85%
17/05/03 04:53:32 INFO mapreduce.Job:  map 100% reduce 87%
17/05/03 04:53:34 INFO mapreduce.Job:  map 100% reduce 88%
17/05/03 04:53:35 INFO mapreduce.Job:  map 100% reduce 90%
17/05/03 04:53:37 INFO mapreduce.Job:  map 100% reduce 91%
17/05/03 04:53:38 INFO mapreduce.Job:  map 100% reduce 92%
17/05/03 04:53:40 INFO mapreduce.Job:  map 100% reduce 93%
17/05/03 04:53:41 INFO mapreduce.Job:  map 100% reduce 94%
17/05/03 04:53:43 INFO mapreduce.Job:  map 100% reduce 95%
17/05/03 04:53:44 INFO mapreduce.Job:  map 100% reduce 97%
17/05/03 04:53:46 INFO mapreduce.Job:  map 100% reduce 98%
17/05/03 04:53:47 INFO mapreduce.Job:  map 100% reduce 99%
17/05/03 04:53:49 INFO mapreduce.Job:  map 100% reduce 100%
17/05/03 04:53:49 INFO mapreduce.Job: Job job_1493779454395_0003 completed successfully
17/05/03 04:53:50 INFO mapreduce.Job: Counters: 49
        File System Counters
                FILE: Number of bytes read=4477847362
                FILE: Number of bytes written=8891270387
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=10000047100
                HDFS: Number of bytes written=10000000000
                HDFS: Number of read operations=918
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=12
        Job Counters
                Launched map tasks=300
                Launched reduce tasks=6
                Data-local map tasks=300
                Total time spent by all maps in occupied slots (ms)=3276345
                Total time spent by all reduces in occupied slots (ms)=648703
                Total time spent by all map tasks (ms)=3276345
                Total time spent by all reduce tasks (ms)=648703
                Total vcore-seconds taken by all map tasks=3276345
                Total vcore-seconds taken by all reduce tasks=648703
                Total megabyte-seconds taken by all map tasks=3354977280
                Total megabyte-seconds taken by all reduce tasks=664271872
        Map-Reduce Framework
                Map input records=100000000
                Map output records=100000000
                Map output bytes=10200000000
                Map output materialized bytes=4375170195
                Input split bytes=47100
                Combine input records=0
                Combine output records=0
                Reduce input groups=100000000
                Reduce shuffle bytes=4375170195
                Reduce input records=100000000
                Reduce output records=100000000
                Spilled Records=200000000
                Shuffled Maps =1800
                Failed Shuffles=0
                Merged Map outputs=1800
                GC time elapsed (ms)=46186
                CPU time spent (ms)=1561490
                Physical memory (bytes) snapshot=145061416960
                Virtual memory (bytes) snapshot=478268862464
                Total committed heap usage (bytes)=173886930944
        Shuffle Errors
                BAD_ID=0
                CONNECTION=0
                IO_ERROR=0
                WRONG_LENGTH=0
                WRONG_MAP=0
                WRONG_REDUCE=0
        File Input Format Counters
                Bytes Read=10000000000
        File Output Format Counters
                Bytes Written=10000000000
17/05/03 04:53:50 INFO terasort.TeraSort: done

real    7m5.811s
user    0m10.965s
sys     0m0.975s

```