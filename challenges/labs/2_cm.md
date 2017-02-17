```
[root@servaed-2 ~]# ls /etc/yum.repos.d
CentOS-Base.repo       CentOS-Media.repo      mysql-community.repo
CentOS-Debuginfo.repo  CentOS-Vault.repo      OpenLogic.repo
CentOS-fasttrack.repo  cloudera-manager.repo
```

```
[root@servaed-2 ~]# /etc/scm_prepare_database.sh mysql -h 10.0.4.4 -P 3306 scm root P@ssw0rd123456
/etc/scm_prepare_database.sh: line 19: /etc/scm_database_functions.sh: No such file or directory
JAVA_HOME=/usr/java/jdk1.7.0_67-cloudera
Verifying that we can write to /etc/cloudera-scm-server
/etc/scm_prepare_database.sh: line 322: check_can_mkdir_path: command not found
/etc/scm_prepare_database.sh: line 323: fail_or_continue: command not found
/etc/scm_prepare_database.sh: line 334: verbose: command not found
/etc/scm_prepare_database.sh: line 335: verbose: command not found
Creating SCM configuration file in /etc/cloudera-scm-server
/etc/scm_prepare_database.sh: line 369: fail_or_continue: command not found
/etc/scm_prepare_database.sh: line 374: fail_or_continue: command not found
/etc/scm_prepare_database.sh: line 382: fail_or_continue: command not found
/etc/scm_prepare_database.sh: line 398: fail_or_continue: command not found
/etc/scm_prepare_database.sh: line 400: fail_or_continue: command not found
/etc/scm_prepare_database.sh: line 401: verbose: command not found
/etc/scm_prepare_database.sh: line 403: verbose: command not found
Executing:  /usr/java/jdk1.7.0_67-cloudera/bin/java -cp /usr/share/java/mysql-connector-java.jar:/usr/share/java/oracle-connector-java.jar:/etc/../lib/* com.cloudera.enterprise.dbutil.DbCommandExecutor /etc/cloudera-scm-server/db.properties com.cloudera.cmf.db.
Error: Could not find or load main class com.cloudera.enterprise.dbutil.DbCommandExecutor
/etc/scm_prepare_database.sh: line 416: fail_or_continue: command not found
All done, your SCM database is configured correctly!
```
