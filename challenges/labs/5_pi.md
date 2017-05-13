```
[jemaine@ip-172-31-43-132 ~]$ hadoop jar /opt/cloudera/parcels/CDH/lib/hadoop-mapreduce/hadoop-mapreduce-examples.jar pi 4 200
Number of Maps  = 4
Samples per Map = 200
Wrote input for Map #0
Wrote input for Map #1
Wrote input for Map #2
Wrote input for Map #3
Starting Job
17/05/13 09:19:49 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-32-147.us-west-2.compute.internal/172.31.32.147:8032
17/05/13 09:19:50 INFO hdfs.DFSClient: Created token for jemaine: HDFS_DELEGATION_TOKEN owner=jemaine@NithK45.AU, renewer=yarn, realUser=, issueDate=1494667190150, maxDate=1495271990150, sequenceNumber=10, masterKeyId=18 on 172.31.43.132:8020
17/05/13 09:19:50 INFO security.TokenCache: Got dt for hdfs://ip-172-31-43-132.us-west-2.compute.internal:8020; Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.43.132:8020, Ident: (token for jemaine: HDFS_DELEGATION_TOKEN owner=jemaine@NithK45.AU, renewer=yarn, realUser=, issueDate=1494667190150, maxDate=1495271990150, sequenceNumber=10, masterKeyId=18)
17/05/13 09:19:50 INFO input.FileInputFormat: Total input paths to process : 4
17/05/13 09:19:50 INFO mapreduce.JobSubmitter: number of splits:4
17/05/13 09:19:50 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1494665324553_0001
17/05/13 09:19:50 INFO mapreduce.JobSubmitter: Kind: HDFS_DELEGATION_TOKEN, Service: 172.31.43.132:8020, Ident: (token for jemaine: HDFS_DELEGATION_TOKEN owner=jemaine@NithK45.AU, renewer=yarn, realUser=, issueDate=1494667190150, maxDate=1495271990150, sequenceNumber=10, masterKeyId=18)
17/05/13 09:19:51 INFO impl.YarnClientImpl: Submitted application application_1494665324553_0001
17/05/13 09:19:51 INFO mapreduce.Job: The url to track the job: http://ip-172-31-32-147.us-west-2.compute.internal:8088/proxy/application_1494665324553_0001/
17/05/13 09:19:51 INFO mapreduce.Job: Running job: job_1494665324553_0001
17/05/13 09:20:03 INFO mapreduce.Job: Job job_1494665324553_0001 running in uber mode : false
17/05/13 09:20:03 INFO mapreduce.Job:  map 0% reduce 0%
17/05/13 09:20:11 INFO mapreduce.Job:  map 50% reduce 0%
17/05/13 09:20:16 INFO mapreduce.Job:  map 100% reduce 0%
17/05/13 09:20:22 INFO mapreduce.Job:  map 100% reduce 100%
17/05/13 09:20:22 INFO mapreduce.Job: Job job_1494665324553_0001 completed successfully
17/05/13 09:20:22 INFO mapreduce.Job: Counters: 53
        File System Counters
                FILE: Number of bytes read=65
                FILE: Number of bytes written=645576
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=1204
                HDFS: Number of bytes written=215
                HDFS: Number of read operations=19
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=3
        Job Counters
                Launched map tasks=4
                Launched reduce tasks=1
                Data-local map tasks=4
                Total time spent by all maps in occupied slots (ms)=31854
                Total time spent by all reduces in occupied slots (ms)=4093
                Total time spent by all map tasks (ms)=31854
                Total time spent by all reduce tasks (ms)=4093
                Total vcore-milliseconds taken by all map tasks=31854
                Total vcore-milliseconds taken by all reduce tasks=4093
                Total megabyte-milliseconds taken by all map tasks=32618496
                Total megabyte-milliseconds taken by all reduce tasks=4191232
        Map-Reduce Framework
                Map input records=4
                Map output records=8
                Map output bytes=72
                Map output materialized bytes=136
                Input split bytes=732
                Combine input records=0
                Combine output records=0
                Reduce input groups=2
                Reduce shuffle bytes=136
                Reduce input records=8
                Reduce output records=0
                Spilled Records=16
                Shuffled Maps =4
                Failed Shuffles=0
                Merged Map outputs=4
                GC time elapsed (ms)=172
                CPU time spent (ms)=4420
                Physical memory (bytes) snapshot=2110615552
                Virtual memory (bytes) snapshot=7829622784
                Total committed heap usage (bytes)=2505048064
                Peak Map Physical memory (bytes)=491393024
                Peak Map Virtual memory (bytes)=1567682560
                Peak Reduce Physical memory (bytes)=193462272
                Peak Reduce Virtual memory (bytes)=1588572160
        Shuffle Errors
                BAD_ID=0
                CONNECTION=0
                IO_ERROR=0
                WRONG_LENGTH=0
                WRONG_MAP=0
                WRONG_REDUCE=0
        File Input Format Counters
                Bytes Read=472
        File Output Format Counters
                Bytes Written=97
Job Finished in 32.681 seconds
Estimated value of Pi is 3.13500000000000000000

```