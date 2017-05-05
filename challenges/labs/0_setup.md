Cloud provider AWS

puplic IPs
```
52.41.21.99 ec2-52-41-21-99.us-west-2.compute.amazonaws.com
34.209.134.10 ec2-34-209-134-10.us-west-2.compute.amazonaws.com
35.165.221.232 ec2-35-165-221-232.us-west-2.compute.amazonaws.com
52.42.98.18 ec2-52-42-98-18.us-west-2.compute.amazonaws.com
34.209.70.106 ec2-34-209-70-106.us-west-2.compute.amazonaws.com
```
internal host names
```
ip-172-31-7-139.us-west-2.compute.internal
ip-172-31-1-20.us-west-2.compute.internal
ip-172-31-15-253.us-west-2.compute.internal
ip-172-31-0-235.us-west-2.compute.internal
ip-172-31-5-166.us-west-2.compute.internal
```

Linux version
```
CentOS 6-5 -x86_64- - Release Media-6-5 
```

Demonstrate the disk capacity available on each node is >= 30 GB
```
[root@ip-172-31-7-139 ~]# df -h
Filesystem      Size  Used Avail Use% Mounted on
/dev/xvde        79G  660M   75G   1% /
tmpfs           7.4G     0  7.4G   0% /dev/shm
[root@ip-172-31-7-139 ~]#

[root@ip-172-31-1-20 ~]# df -h
Filesystem      Size  Used Avail Use% Mounted on
/dev/xvde        79G  661M   75G   1% /
tmpfs           7.4G     0  7.4G   0% /dev/shm


[root@ip-172-31-15-253 ~]# df -h
Filesystem      Size  Used Avail Use% Mounted on
/dev/xvde        79G  660M   75G   1% /
tmpfs           7.4G     0  7.4G   0% /dev/shm


[root@ip-172-31-0-235 ~]# df -h
Filesystem      Size  Used Avail Use% Mounted on
/dev/xvde        79G  660M   75G   1% /
tmpfs           7.4G     0  7.4G   0% /dev/shm

[root@ip-172-31-5-166 ~]# df -h
Filesystem      Size  Used Avail Use% Mounted on
/dev/xvde        79G  660M   75G   1% /
tmpfs           7.4G     0  7.4G   0% /dev/shm


```

List the command and output for yum repolist enabled
```
[root@ip-172-31-7-139 ~]# yum repolist enabled
Loaded plugins: fastestmirror, presto
Determining fastest mirrors
 * base: mirrors.sonic.net
 * extras: repos.lax.quadranet.com
 * updates: mirrors.sonic.net
repo id                        repo name                                  status
base                           CentOS-6 - Base                            6,706
extras                         CentOS-6 - Extras                             64
updates                        CentOS-6 - Updates                           252
repolist: 7,022
```

List the /etc/passwd entries for cate and jemaine
```
cate:x:2300:2000::/home/cate:/bin/bash
jemaine:x:2900:2200::/home/jemaine:/bin/bash
```

List the /etc/group entries for kiwis and aussies
```
aussies:x:2000:
kiwis:x:2200:
```

