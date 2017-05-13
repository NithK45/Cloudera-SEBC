```
[cate@ip-172-31-43-132 ~]$ time hadoop jar /opt/cloudera/parcels/CDH-5.11.0-1.cdh5.11.0.p0.34/lib/hadoop-mapreduce/hadoop-mapreduce-examples-2.6.0-cdh5.11.0.jar terasort /user/cate/tgen1 /user/cate/tsort640m
17/05/13 10:19:51 INFO terasort.TeraSort: starting
17/05/13 10:19:53 INFO hdfs.DFSClient: Created token for cate: HDFS_DELEGATION_TOKEN owner=cate@NithK45.AU, renewer=yarn, realUser=, issueDate=1494670793566, maxDate=1495275593566, sequenceNumber=15, masterKeyId=26 on 172.31.43.132:8020
17/05/13 10:19:53 INFO security.TokenCache: Got dt for hdfs://ip-172-31-43-132.us-west-2.compute.internal:8020; Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.43.132:8020, Ident: (token for cate: HDFS_DELEGATION_TOKEN owner=cate@NithK45.AU, renewer=yarn, realUser=, issueDate=1494670793566, maxDate=1495275593566, sequenceNumber=15, masterKeyId=26)
17/05/13 10:19:53 INFO input.FileInputFormat: Total input paths to process : 8
Spent 600ms computing base-splits.
Spent 14ms computing TeraScheduler splits.
Computing input splits took 615ms
Sampling 10 splits of 616
Making 8 from 1639 sampled records
Computing parititions took 500ms
Spent 1118ms computing partitions.
17/05/13 10:19:54 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-32-147.us-west-2.compute.internal/172.31.32.147:8032
17/05/13 10:19:54 INFO mapreduce.JobSubmitter: number of splits:616
17/05/13 10:19:55 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1494669775607_0002
17/05/13 10:19:55 INFO mapreduce.JobSubmitter: Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.43.132:8020, Ident: (token for cate: HDFS_DELEGATION_TOKEN owner=cate@NithK45.AU, renewer=yarn, realUser=, issueDate=1494670793566, maxDate=1495275593566, sequenceNumber=15, masterKeyId=26)
17/05/13 10:19:55 INFO impl.YarnClientImpl: Submitted application application_1494669775607_0002
17/05/13 10:19:55 INFO mapreduce.Job: The url to track the job: http://ip-172-31-32-147.us-west-2.compute.internal:8088/proxy/application_1494669775607_0002/
17/05/13 10:19:55 INFO mapreduce.Job: Running job: job_1494669775607_0002
17/05/13 10:20:06 INFO mapreduce.Job: Job job_1494669775607_0002 running in uber mode : false
17/05/13 10:20:06 INFO mapreduce.Job:  map 0% reduce 0%
17/05/13 10:20:20 INFO mapreduce.Job:  map 1% reduce 0%
17/05/13 10:20:21 INFO mapreduce.Job:  map 2% reduce 0%
17/05/13 10:20:29 INFO mapreduce.Job:  map 3% reduce 0%
17/05/13 10:20:31 INFO mapreduce.Job:  map 4% reduce 0%
17/05/13 10:20:37 INFO mapreduce.Job:  map 5% reduce 0%
17/05/13 10:20:42 INFO mapreduce.Job:  map 6% reduce 0%
17/05/13 10:20:46 INFO mapreduce.Job:  map 7% reduce 0%
17/05/13 10:20:53 INFO mapreduce.Job:  map 8% reduce 0%
17/05/13 10:20:58 INFO mapreduce.Job:  map 9% reduce 0%
17/05/13 10:21:02 INFO mapreduce.Job:  map 10% reduce 0%
17/05/13 10:21:08 INFO mapreduce.Job:  map 11% reduce 0%
17/05/13 10:21:10 INFO mapreduce.Job:  map 12% reduce 0%
17/05/13 10:21:17 INFO mapreduce.Job:  map 13% reduce 0%
17/05/13 10:21:23 INFO mapreduce.Job:  map 14% reduce 0%
17/05/13 10:21:26 INFO mapreduce.Job:  map 15% reduce 0%
17/05/13 10:21:32 INFO mapreduce.Job:  map 16% reduce 0%
17/05/13 10:21:35 INFO mapreduce.Job:  map 17% reduce 0%
17/05/13 10:21:41 INFO mapreduce.Job:  map 18% reduce 0%
17/05/13 10:21:46 INFO mapreduce.Job:  map 19% reduce 0%
17/05/13 10:21:50 INFO mapreduce.Job:  map 20% reduce 0%
17/05/13 10:21:57 INFO mapreduce.Job:  map 21% reduce 0%
17/05/13 10:21:59 INFO mapreduce.Job:  map 22% reduce 0%
17/05/13 10:22:06 INFO mapreduce.Job:  map 23% reduce 0%
17/05/13 10:22:10 INFO mapreduce.Job:  map 24% reduce 0%
17/05/13 10:22:14 INFO mapreduce.Job:  map 25% reduce 0%
17/05/13 10:22:20 INFO mapreduce.Job:  map 26% reduce 0%
17/05/13 10:22:24 INFO mapreduce.Job:  map 27% reduce 0%
17/05/13 10:22:30 INFO mapreduce.Job:  map 28% reduce 0%
17/05/13 10:22:34 INFO mapreduce.Job:  map 29% reduce 0%
17/05/13 10:22:39 INFO mapreduce.Job:  map 30% reduce 0%
17/05/13 10:22:42 INFO mapreduce.Job:  map 31% reduce 0%
17/05/13 10:22:47 INFO mapreduce.Job:  map 32% reduce 0%
17/05/13 10:22:54 INFO mapreduce.Job:  map 33% reduce 0%
17/05/13 10:22:57 INFO mapreduce.Job:  map 34% reduce 0%
17/05/13 10:23:03 INFO mapreduce.Job:  map 35% reduce 0%
17/05/13 10:23:07 INFO mapreduce.Job:  map 36% reduce 0%
17/05/13 10:23:12 INFO mapreduce.Job:  map 37% reduce 0%
17/05/13 10:23:18 INFO mapreduce.Job:  map 38% reduce 0%
17/05/13 10:23:23 INFO mapreduce.Job:  map 39% reduce 0%
17/05/13 10:23:27 INFO mapreduce.Job:  map 40% reduce 0%
17/05/13 10:23:33 INFO mapreduce.Job:  map 41% reduce 0%
17/05/13 10:23:36 INFO mapreduce.Job:  map 42% reduce 0%
17/05/13 10:23:42 INFO mapreduce.Job:  map 43% reduce 0%
17/05/13 10:23:45 INFO mapreduce.Job:  map 44% reduce 0%
17/05/13 10:23:51 INFO mapreduce.Job:  map 45% reduce 0%
17/05/13 10:23:55 INFO mapreduce.Job:  map 46% reduce 0%
17/05/13 10:24:01 INFO mapreduce.Job:  map 47% reduce 0%
17/05/13 10:24:07 INFO mapreduce.Job:  map 48% reduce 0%
17/05/13 10:24:10 INFO mapreduce.Job:  map 49% reduce 0%
17/05/13 10:24:15 INFO mapreduce.Job:  map 50% reduce 0%
17/05/13 10:24:20 INFO mapreduce.Job:  map 51% reduce 0%
17/05/13 10:24:25 INFO mapreduce.Job:  map 52% reduce 0%
17/05/13 10:24:31 INFO mapreduce.Job:  map 53% reduce 0%
17/05/13 10:24:35 INFO mapreduce.Job:  map 54% reduce 0%
17/05/13 10:24:40 INFO mapreduce.Job:  map 55% reduce 0%
17/05/13 10:24:43 INFO mapreduce.Job:  map 56% reduce 0%
17/05/13 10:24:50 INFO mapreduce.Job:  map 57% reduce 0%
17/05/13 10:24:55 INFO mapreduce.Job:  map 58% reduce 0%
17/05/13 10:24:59 INFO mapreduce.Job:  map 59% reduce 0%
17/05/13 10:25:04 INFO mapreduce.Job:  map 60% reduce 0%
17/05/13 10:25:07 INFO mapreduce.Job:  map 61% reduce 0%
17/05/13 10:25:13 INFO mapreduce.Job:  map 62% reduce 0%
17/05/13 10:25:19 INFO mapreduce.Job:  map 63% reduce 0%
17/05/13 10:25:23 INFO mapreduce.Job:  map 64% reduce 0%
17/05/13 10:25:28 INFO mapreduce.Job:  map 65% reduce 0%
17/05/13 10:25:33 INFO mapreduce.Job:  map 66% reduce 0%
17/05/13 10:25:38 INFO mapreduce.Job:  map 67% reduce 0%
17/05/13 10:25:43 INFO mapreduce.Job:  map 68% reduce 0%
17/05/13 10:25:47 INFO mapreduce.Job:  map 69% reduce 0%
17/05/13 10:25:54 INFO mapreduce.Job:  map 70% reduce 0%
17/05/13 10:25:58 INFO mapreduce.Job:  map 71% reduce 0%
17/05/13 10:26:02 INFO mapreduce.Job:  map 72% reduce 0%
17/05/13 10:26:07 INFO mapreduce.Job:  map 73% reduce 0%
17/05/13 10:26:11 INFO mapreduce.Job:  map 74% reduce 0%
17/05/13 10:26:15 INFO mapreduce.Job:  map 75% reduce 0%
17/05/13 10:26:24 INFO mapreduce.Job:  map 76% reduce 0%
17/05/13 10:26:27 INFO mapreduce.Job:  map 77% reduce 0%
17/05/13 10:26:33 INFO mapreduce.Job:  map 78% reduce 0%
17/05/13 10:26:38 INFO mapreduce.Job:  map 79% reduce 0%
17/05/13 10:26:43 INFO mapreduce.Job:  map 80% reduce 0%
17/05/13 10:26:48 INFO mapreduce.Job:  map 81% reduce 0%
17/05/13 10:26:52 INFO mapreduce.Job:  map 82% reduce 0%
17/05/13 10:26:59 INFO mapreduce.Job:  map 83% reduce 0%
17/05/13 10:27:06 INFO mapreduce.Job:  map 83% reduce 3%
17/05/13 10:27:07 INFO mapreduce.Job:  map 84% reduce 7%
17/05/13 10:27:08 INFO mapreduce.Job:  map 84% reduce 14%
17/05/13 10:27:15 INFO mapreduce.Job:  map 85% reduce 14%
17/05/13 10:27:23 INFO mapreduce.Job:  map 86% reduce 14%
17/05/13 10:27:30 INFO mapreduce.Job:  map 87% reduce 14%
17/05/13 10:27:38 INFO mapreduce.Job:  map 88% reduce 15%
17/05/13 10:27:46 INFO mapreduce.Job:  map 89% reduce 15%
17/05/13 10:27:54 INFO mapreduce.Job:  map 90% reduce 15%
17/05/13 10:28:01 INFO mapreduce.Job:  map 91% reduce 15%
17/05/13 10:28:10 INFO mapreduce.Job:  map 92% reduce 15%
17/05/13 10:28:17 INFO mapreduce.Job:  map 93% reduce 15%
17/05/13 10:28:25 INFO mapreduce.Job:  map 94% reduce 15%
17/05/13 10:28:26 INFO mapreduce.Job:  map 94% reduce 16%
17/05/13 10:28:34 INFO mapreduce.Job:  map 95% reduce 16%
17/05/13 10:28:41 INFO mapreduce.Job:  map 96% reduce 16%
17/05/13 10:28:50 INFO mapreduce.Job:  map 97% reduce 16%
17/05/13 10:28:56 INFO mapreduce.Job:  map 98% reduce 16%
17/05/13 10:29:06 INFO mapreduce.Job:  map 99% reduce 16%
17/05/13 10:29:11 INFO mapreduce.Job:  map 100% reduce 16%
17/05/13 10:29:13 INFO mapreduce.Job:  map 100% reduce 17%
17/05/13 10:29:19 INFO mapreduce.Job:  map 100% reduce 56%
17/05/13 10:29:20 INFO mapreduce.Job:  map 100% reduce 75%
17/05/13 10:29:21 INFO mapreduce.Job:  map 100% reduce 88%
17/05/13 10:29:24 INFO mapreduce.Job:  map 100% reduce 100%
17/05/13 10:29:24 INFO mapreduce.Job: Job job_1494669775607_0002 completed successfully
17/05/13 10:29:24 INFO mapreduce.Job: Counters: 54
        File System Counters
                FILE: Number of bytes read=4405183
                FILE: Number of bytes written=90146632
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=10091784
                HDFS: Number of bytes written=10000000
                HDFS: Number of read operations=1872
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=16
        Job Counters
                Launched map tasks=616
                Launched reduce tasks=8
                Data-local map tasks=615
                Rack-local map tasks=1
                Total time spent by all maps in occupied slots (ms)=3739275
                Total time spent by all reduces in occupied slots (ms)=622353
                Total time spent by all map tasks (ms)=3739275
                Total time spent by all reduce tasks (ms)=622353
                Total vcore-milliseconds taken by all map tasks=3739275
                Total vcore-milliseconds taken by all reduce tasks=622353
                Total megabyte-milliseconds taken by all map tasks=3829017600
                Total megabyte-milliseconds taken by all reduce tasks=637289472
        Map-Reduce Framework
                Map input records=100000
                Map output records=100000
                Map output bytes=10200000
                Map output materialized bytes=4700119
                Input split bytes=91784
                Combine input records=0
                Combine output records=0
                Reduce input groups=100000
                Reduce shuffle bytes=4700119
                Reduce input records=100000
                Reduce output records=100000
                Spilled Records=200000
                Shuffled Maps =4928
                Failed Shuffles=0
                Merged Map outputs=4928
                GC time elapsed (ms)=26311
                CPU time spent (ms)=606150
                Physical memory (bytes) snapshot=289067270144
                Virtual memory (bytes) snapshot=976943857664
                Total committed heap usage (bytes)=326437437440
                Peak Map Physical memory (bytes)=515174400
                Peak Map Virtual memory (bytes)=1581363200
                Peak Reduce Physical memory (bytes)=292790272
                Peak Reduce Virtual memory (bytes)=1590878208
        Shuffle Errors
                BAD_ID=0
                CONNECTION=0
                IO_ERROR=0
                WRONG_LENGTH=0
                WRONG_MAP=0
                WRONG_REDUCE=0
        File Input Format Counters
                Bytes Read=10000000
        File Output Format Counters
                Bytes Written=10000000
17/05/13 10:29:24 INFO terasort.TeraSort: done

real    9m34.022s
user    0m9.486s
sys     0m1.136s
[cate@ip-172-31-43-132 ~]$

```