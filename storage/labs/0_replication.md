
1. Use hdfs fsck <path> -files -blocks on source directory

command used
```
hdfs fsck /user/NithK45/0_replication_source_NithK45/ -files -blocks
```
output
```
[hdfs@ip-172-31-38-19 ~]$ hdfs fsck /user/NithK45/0_replication_source_NithK45/ -files -blocks
Connecting to namenode via http://ip-172-31-38-19.us-west-2.compute.internal:50070
FSCK started by hdfs (auth:SIMPLE) from /172.31.38.19 for path /user/NithK45/0_replication_source_NithK45/ at Wed May 03 03:35:15 UTC 2017
/user/NithK45/0_replication_source_NithK45/ <dir>
/user/NithK45/0_replication_source_NithK45/_SUCCESS 0 bytes, 0 block(s):  OK

/user/NithK45/0_replication_source_NithK45/part-m-00000 290000000 bytes, 3 block(s):  OK
0. BP-1229735846-172.31.38.19-1493729570508:blk_1073743374_2550 len=134217728 Live_repl=3
1. BP-1229735846-172.31.38.19-1493729570508:blk_1073743376_2552 len=134217728 Live_repl=3
2. BP-1229735846-172.31.38.19-1493729570508:blk_1073743378_2554 len=21564544 Live_repl=3

/user/NithK45/0_replication_source_NithK45/part-m-00001 290000000 bytes, 3 block(s):  OK
0. BP-1229735846-172.31.38.19-1493729570508:blk_1073743375_2551 len=134217728 Live_repl=3
1. BP-1229735846-172.31.38.19-1493729570508:blk_1073743377_2553 len=134217728 Live_repl=3
2. BP-1229735846-172.31.38.19-1493729570508:blk_1073743380_2556 len=21564544 Live_repl=3

Status: HEALTHY
 Total size:    580000000 B
 Total dirs:    1
 Total files:   3
 Total symlinks:                0
 Total blocks (validated):      6 (avg. block size 96666666 B)
 Minimally replicated blocks:   6 (100.0 %)
 Over-replicated blocks:        0 (0.0 %)
 Under-replicated blocks:       0 (0.0 %)
 Mis-replicated blocks:         0 (0.0 %)
 Default replication factor:    3
 Average block replication:     3.0
 Corrupt blocks:                0
 Missing replicas:              0 (0.0 %)
 Number of data-nodes:          3
 Number of racks:               1
FSCK ended at Wed May 03 03:35:15 UTC 2017 in 3 milliseconds


The filesystem under path '/user/NithK45/0_replication_source_NithK45/' is HEALTHY
```

2. Pull file from partner system, (taking too long to transfer 500mb file, couldnt finish)

command used

```
hadoop distcp hdfs://52.65.113.189:8020/user/idiotek/0_replication_source_idiotek/ hdfs://ec2-34-210-17-89.us-west-2.compute.amazonaws.com:8020/user/NithK45/0_replication_target_NithK45/
```