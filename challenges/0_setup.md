Cloud Provider: Azure

Linux Release : CentOS 6.8

![1](https://github.com/servaed/SEBC/blob/master/challenges/Disk%20Space.PNG)

```
[root@servaed-1 ~]# yum repolist enabled
Loaded plugins: fastestmirror, security
base                                                     | 3.7 kB     00:00
base/primary_db                                          | 4.7 MB     00:00
extras                                                   | 3.4 kB     00:00
extras/primary_db                                        |  37 kB     00:00
openlogic                                                | 2.9 kB     00:00
openlogic/primary_db                                     | 537 kB     00:00
updates                                                  | 3.4 kB     00:00
updates/primary_db                                       | 4.3 MB     00:00
repo id              repo name                                            status
base                 CentOS-6 - Base                                      6,696
extras               CentOS-6 - Extras                                       63
openlogic            CentOS-6 - openlogic packages for x86_64                32
updates              CentOS-6 - Updates                                     825
repolist: 7,616
```
```
[root@servaed-1 ~]# grep raffles /etc/passwd
raffles:x:2000:2000::/home/raffles:/bin/bash
[root@servaed-1 ~]# grep fullerton /etc/passwd
fullerton:x:3000:3000::/home/fullerton:/bin/bash
[root@servaed-1 ~]# grep hotels /etc/group
hotels:x:3001:fullerton
[root@servaed-1 ~]# grep shops /etc/group
shops:x:2001:raffles
```

```
[root@servaed-2 ~]# grep raffles /etc/passwd
raffles:x:2000:2000::/home/raffles:/bin/bash
[root@servaed-2 ~]# grep fullerton /etc/passwd
fullerton:x:3000:3000::/home/fullerton:/bin/bash
[root@servaed-2 ~]# grep hotels /etc/group
hotels:x:3001:fullerton
[root@servaed-2 ~]# grep shops /etc/group
shops:x:2001:raffles
```

```
[root@servaed-3 ~]# grep raffles /etc/passwd
raffles:x:2000:2000::/home/raffles:/bin/bash
[root@servaed-3 ~]# grep fullerton /etc/passwd
fullerton:x:3000:3000::/home/fullerton:/bin/bash
[root@servaed-3 ~]# grep hotels /etc/group
hotels:x:3001:fullerton
[root@servaed-3 ~]# grep shops /etc/group
shops:x:2001:raffles
```

```
[root@servaed-4 ~]# grep raffles /etc/passwd
raffles:x:2000:2000::/home/raffles:/bin/bash
[root@servaed-4 ~]# grep fullerton /etc/passwd
fullerton:x:3000:3000::/home/fullerton:/bin/bash
[root@servaed-4 ~]# grep hotels /etc/group
hotels:x:3001:fullerton
[root@servaed-4 ~]# grep shops /etc/group
shops:x:2001:raffles
```

```
[root@servaed-5 ~]# grep raffles /etc/passwd
raffles:x:2000:2000::/home/raffles:/bin/bash
[root@servaed-5 ~]# grep fullerton /etc/passwd
fullerton:x:3000:3000::/home/fullerton:/bin/bash
[root@servaed-5 ~]# grep hotels /etc/group
hotels:x:3001:fullerton
[root@servaed-5 ~]# grep shops /etc/group
shops:x:2001:raffles
```
