The hostname of your db server node

```
[root@ip-172-31-7-139 ~]# hostname
ip-172-31-7-139
[root@ip-172-31-7-139 ~]# hostname -f
ip-172-31-7-139.us-west-2.compute.internal
```


The command and output for display your database server's version

```
mysql> SHOW VARIABLES LIKE "%version%";
+-------------------------+------------------------------+
| Variable_name           | Value                        |
+-------------------------+------------------------------+
| innodb_version          | 5.6.36                       |
| protocol_version        | 10                           |
| slave_type_conversions  |                              |
| version                 | 5.6.36                       |
| version_comment         | MySQL Community Server (GPL) |
| version_compile_machine | x86_64                       |
| version_compile_os      | Linux                        |
+-------------------------+------------------------------+
7 rows in set (0.00 sec)


```
The command and output for listing your created databases
```
mysql> show databases;
+--------------------+
| Database           |
+--------------------+
| information_schema |
| hive               |
| hue                |
| mysql              |
| oozie              |
| performance_schema |
| rman               |
| scm                |
| sentry             |
+--------------------+
9 rows in set (0.00 sec)

```