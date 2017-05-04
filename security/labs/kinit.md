```
[root@ip-172-31-45-130 ~]# kinit cloudera-scm/admin@SEBCNithK45.COM
Password for cloudera-scm/admin@SEBCNithK45.COM:
[root@ip-172-31-45-130 ~]# klist
Ticket cache: FILE:/tmp/krb5cc_0
Default principal: cloudera-scm/admin@SEBCNithK45.COM

Valid starting     Expires            Service principal
05/04/17 12:51:21  05/05/17 12:51:21  krbtgt/SEBCNithK45.COM@SEBCNithK45.COM
        renew until 05/11/17 12:51:21
[root@ip-172-31-45-130 ~]#
```

with user named after github handle

```
[root@ip-172-31-45-130 ~]# kinit NithK45/admin@SEBCNithK45.COM
Password for NithK45/admin@SEBCNithK45.COM:
[root@ip-172-31-45-130 ~]# klist
Ticket cache: FILE:/tmp/krb5cc_0
Default principal: NithK45/admin@SEBCNithK45.COM

Valid starting     Expires            Service principal
05/04/17 12:58:17  05/05/17 12:58:17  krbtgt/SEBCNithK45.COM@SEBCNithK45.COM
        renew until 05/11/17 12:58:17

```