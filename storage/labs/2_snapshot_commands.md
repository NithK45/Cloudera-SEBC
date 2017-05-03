
1. commands for testing HDFS snapshots
```
hadoop fs -put SEBC_NithK45.zip /user/NithK45/precious/
su - hdfs
hdfs dfsadmin -allowSnapshot /user/NithK45/precious/
hdfs dfs -createSnapshot /user/NithK45/precious/ sebc-hdfs-test 
hadoop fs -rm -r /user/NithK45/precious
hadoop fs -rm -r /user/NithK45/precious/SEBC_NithK45.zip 
hadoop fs -cp /user/NithK45/precious/.snapshot/sebc-hdfs-test/SEBC_NithK45.zip /user/NithK45/precious/
```