---
layout: post
title: "NETAPP存储设备日志分析"
categories: [日志分析]
tags: [log,netapp]
---

# /etc/messages
[sample data](/attach/netapp/message.txt)

# /etc/log/auditlog
[sample data](/attach/netapp/auditlog.txt)


# sysstat
[sysstat系统性能信息，需要收集]
```
fas3240> sysstat
 CPU     NFS    CIFS    HTTP     Net   kB/s    Disk   kB/s    Tape   kB/s  Cache
                                  in    out    read  write    read  write    age
 20%    2512       0       0   15630  49018   54271  21051       0      0     3s
 32%    3730       0       0   16091 101910  113097  22304       0      0     3s
fas3240> 
```

## netapp log 方式

## ACP log

path: /etc/log/acp

```
-rw-r--r--@   2 polinchen  staff     0 12 13  2015 acplog_master
-rw-r--r--@   2 polinchen  staff  1718 12  7  2015 acplog_master.10
-rw-r--r--@   2 polinchen  staff     0 12 13  2015 acplog_master.log.0000000000
-rw-r--r--@   1 polinchen  staff  2416 12  5  2015 acplog_master.log.0000000001
-rw-r--r--@   2 polinchen  staff  1718 12  7  2015 acplog_master.log.0000000002
```

content:

```
*Sat Dec  5 13:24:16 GMT 2015; =====================================================================================
*Sat Dec  5 13:24:16 GMT 2015;  ACPA RE-ENABLED OR STORAGE CONTROLLER REBOOTED on ( Sat-Dec--5-13:24:16-GMT-2015 )
*Sat Dec  5 13:24:16 GMT 2015; =====================================================================================
*Sat Dec  5 21:58:33 CST 2015; State of platform ACP port 0 changed to 255.
*Sat Dec  5 21:58:33 CST 2015; State of platform ACP port 1 changed to 255.
*Sat Dec  5 21:58:33 CST 2015; State of platform ACP port 2 changed to 255.
```

## audit : only for 稽核查詢

Path: /etc/log

```
-rw-r--r--@ 2 polinchen  staff  6063525  2 25 00:14 auditlog
-rw-r--r--@ 2 polinchen  staff  7141134  2 19 00:20 auditlog.0
-rw-r--r--@ 2 polinchen  staff  7108767  2 12 00:14 auditlog.1
-rw-r--r--@ 2 polinchen  staff  7141134  2  5 00:22 auditlog.2
-rw-r--r--@ 2 polinchen  staff  7074987  1 29 00:19 auditlog.3
-rw-r--r--@ 1 polinchen  staff  7144488  1 22 00:31 auditlog.4
-rw-r--r--@ 1 polinchen  staff  7119217  1 15 00:21 auditlog.5
-rw-r--r--@ 2 polinchen  staff  7074987  1 29 00:19 auditlog.log.0000000061
-rw-r--r--@ 2 polinchen  staff  7141134  2  5 00:22 auditlog.log.0000000062
-rw-r--r--@ 2 polinchen  staff  7108767  2 12 00:14 auditlog.log.0000000063
-rw-r--r--@ 2 polinchen  staff  7141134  2 19 00:20 auditlog.log.0000000064
-rw-r--r--@ 2 polinchen  staff  6063525  2 25 00:14 auditlog.log.0000000065

```
auditlog

```
Sat Feb 25 00:14:01 CST [NetApp-cluster-dr-02:rshd_4:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_662]:IN:node shell:RSH INPUT COMMAND is priv set -q diag ; df -A -h
Sat Feb 25 00:14:01 CST [NetApp-cluster-dr-02:rshd_4:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_662]:END:node shell:
Sat Feb 25 00:14:01 CST [NetApp-cluster-dr-02:rshd_1:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_620]:END:node shell:
Sat Feb 25 00:14:01 CST [NetApp-cluster-dr-02:rshd_3:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_656]:END:node shell:
Sat Feb 25 00:14:01 CST [NetApp-cluster-dr-02:rshd_2:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_856]:END:node shell:
Sat Feb 25 00:14:02 CST [NetApp-cluster-dr-02:rshd_1:debug]: NetApp-cluster-dr%root%admin:START:node shell:[127.0.10.1_723]
Sat Feb 25 00:14:02 CST [NetApp-cluster-dr-02:rshd_1:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_723]:IN:node shell:RSH INPUT COMMAND is priv set -q diag ; rdfile /etc/registry
Sat Feb 25 00:14:02 CST [NetApp-cluster-dr-02:rshd_1:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_723]:END:node shell:
Sat Feb 25 00:14:02 CST [NetApp-cluster-dr-02:rshd_2:debug]: NetApp-cluster-dr%root%admin:START:node shell:[127.0.10.1_725]
Sat Feb 25 00:14:02 CST [NetApp-cluster-dr-02:rshd_2:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_725]:IN:node shell:RSH INPUT COMMAND is priv set -q diag ; rdfile /etc/rc
Sat Feb 25 00:14:02 CST [NetApp-cluster-dr-02:rshd_2:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_725]:END:node shell:
Sat Feb 25 00:14:03 CST [NetApp-cluster-dr-02:rshd_0:debug]: sumnerTunnel:command is 'usb_info' '0' '1' '32902' '10554' '0a':sent to mhost
Sat Feb 25 00:14:03 CST [NetApp-cluster-dr-02:rshd_0:debug]: sumnerTunnel:command is 'usb_info' '0' '1' '32902' '10554' '0a':command exit status: 0
Sat Feb 25 00:14:03 CST [NetApp-cluster-dr-02:rshd_0:debug]: sumnerTunnel:command is 'usb_info' '0' '1' '32902' '10554' '0a':mhost_exec_internal return status: 0
Sat Feb 25 00:14:03 CST [NetApp-cluster-dr-02:rshd_0:debug]: sumnerTunnel:command is 'usb_info' '0' '1' '32902' '10556' '0b':sent to mhost
Sat Feb 25 00:14:03 CST [NetApp-cluster-dr-02:rshd_0:debug]: sumnerTunnel:command is 'usb_info' '0' '1' '32902' '10556' '0b':command exit status: 1
Sat Feb 25 00:14:03 CST [NetApp-cluster-dr-02:rshd_0:debug]: sumnerTunnel:command is 'usb_info' '0' '1' '32902' '10556' '0b':mhost_exec_internal return status: 0
Sat Feb 25 00:14:03 CST [NetApp-cluster-dr-02:rshd_0:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_813]:END:node shell:
```

auditlog.log.0000000065

```
Sat Feb 25 00:14:01 CST [NetApp-cluster-dr-02:rshd_3:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_656]:IN:node shell:RSH INPUT COMMAND is priv set -q diag ; df
Sat Feb 25 00:14:01 CST [NetApp-cluster-dr-02:rshd_4:debug]: NetApp-cluster-dr%root%admin:START:node shell:[127.0.10.1_662]
Sat Feb 25 00:14:01 CST [NetApp-cluster-dr-02:rshd_4:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_662]:IN:node shell:RSH INPUT COMMAND is priv set -q diag ; df -A -h
Sat Feb 25 00:14:01 CST [NetApp-cluster-dr-02:rshd_4:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_662]:END:node shell:
Sat Feb 25 00:14:01 CST [NetApp-cluster-dr-02:rshd_1:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_620]:END:node shell:
Sat Feb 25 00:14:01 CST [NetApp-cluster-dr-02:rshd_3:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_656]:END:node shell:
Sat Feb 25 00:14:01 CST [NetApp-cluster-dr-02:rshd_2:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_856]:END:node shell:
Sat Feb 25 00:14:02 CST [NetApp-cluster-dr-02:rshd_1:debug]: NetApp-cluster-dr%root%admin:START:node shell:[127.0.10.1_723]
Sat Feb 25 00:14:02 CST [NetApp-cluster-dr-02:rshd_1:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_723]:IN:node shell:RSH INPUT COMMAND is priv set -q diag ; rdfile /etc/registry
Sat Feb 25 00:14:02 CST [NetApp-cluster-dr-02:rshd_1:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_723]:END:node shell:
Sat Feb 25 00:14:02 CST [NetApp-cluster-dr-02:rshd_2:debug]: NetApp-cluster-dr%root%admin:START:node shell:[127.0.10.1_725]
Sat Feb 25 00:14:02 CST [NetApp-cluster-dr-02:rshd_2:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_725]:IN:node shell:RSH INPUT COMMAND is priv set -q diag ; rdfile /etc/rc
Sat Feb 25 00:14:02 CST [NetApp-cluster-dr-02:rshd_2:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_725]:END:node shell:
Sat Feb 25 00:14:03 CST [NetApp-cluster-dr-02:rshd_0:debug]: sumnerTunnel:command is 'usb_info' '0' '1' '32902' '10554' '0a':sent to mhost
Sat Feb 25 00:14:03 CST [NetApp-cluster-dr-02:rshd_0:debug]: sumnerTunnel:command is 'usb_info' '0' '1' '32902' '10554' '0a':command exit status: 0
Sat Feb 25 00:14:03 CST [NetApp-cluster-dr-02:rshd_0:debug]: sumnerTunnel:command is 'usb_info' '0' '1' '32902' '10554' '0a':mhost_exec_internal return status: 0
Sat Feb 25 00:14:03 CST [NetApp-cluster-dr-02:rshd_0:debug]: sumnerTunnel:command is 'usb_info' '0' '1' '32902' '10556' '0b':sent to mhost
Sat Feb 25 00:14:03 CST [NetApp-cluster-dr-02:rshd_0:debug]: sumnerTunnel:command is 'usb_info' '0' '1' '32902' '10556' '0b':command exit status: 1
Sat Feb 25 00:14:03 CST [NetApp-cluster-dr-02:rshd_0:debug]: sumnerTunnel:command is 'usb_info' '0' '1' '32902' '10556' '0b':mhost_exec_internal return status: 0
Sat Feb 25 00:14:03 CST [NetApp-cluster-dr-02:rshd_0:debug]: NetApp-cluster-dr%root%admin@[127.0.10.1_813]:END:node shell:
```

## backup: 

## /etc/log/mlog: 

```
-rw-r--r--@ 2 polinchen  staff    22451  2 19 00:25 apache_access.log
-rw-r--r--@ 2 polinchen  staff    26660  1 10  2016 apache_error.log
-rw-r--r--@ 2 polinchen  staff        0  2 24 21:55 bcomd.log
-rw-r--r--@ 2 polinchen  staff     5456  2 25 00:11 cm-daemon.log
-rw-r--r--@ 2 polinchen  staff    90035  2 25 00:14 command-history.log
-rw-r--r--@ 2 polinchen  staff        0  2 24 21:55 crs.log
-rw-r--r--@ 2 polinchen  staff     1253  2 25 00:14 debug.log
-rw-r--r--@ 2 polinchen  staff        0  2 24 21:55 fpolicy.log
-rw-r--r--@ 2 polinchen  staff        0  2 24 21:55 hashd.log
-rw-r--r--@ 1 polinchen  staff      422 12  7  2015 jm-restart.log
-rw-r--r--@ 1 polinchen  staff     2761 12  7  2015 memsnap-coresegd.log
-rw-r--r--@ 1 polinchen  staff     2280 12  7  2015 memsnap-cphmd.log
-rw-r--r--@ 1 polinchen  staff     2354 12  7  2015 memsnap-cshmd.log
-rw-r--r--@ 1 polinchen  staff     2360 12  7  2015 memsnap-fpolicy.log
-rw-r--r--@ 1 polinchen  staff     1971 12  7  2015 memsnap-httpd.log
-rw-r--r--@ 1 polinchen  staff     2680 12  7  2015 memsnap-mdnsd.log
-rw-r--r--@ 1 polinchen  staff     3853 12  7  2015 memsnap-mhostexecd.log
-rw-r--r--@ 1 polinchen  staff     2596 12  7  2015 memsnap-nchmd.log
-rw-r--r--@ 1 polinchen  staff     2053 12  7  2015 memsnap-ndmpd.log
-rw-r--r--@ 1 polinchen  staff     2673 12  7  2015 memsnap-nphmd.log
-rw-r--r--@ 1 polinchen  staff     1977 12  7  2015 memsnap-php-fpm.log
-rw-r--r--@ 1 polinchen  staff     2204 12  7  2015 memsnap-schmd.log
-rw-r--r--@ 1 polinchen  staff     2763 12  7  2015 memsnap-servprocd.log
-rw-r--r--@ 1 polinchen  staff     2128 12  7  2015 memsnap-shmd.log
-rw-r--r--@ 2 polinchen  staff    76993  2 25 00:17 messages.log
-rw-r--r--@ 2 polinchen  staff   268343  2 25 00:18 mgwd.log
-rw-r--r--@ 2 polinchen  staff        0  2 24 21:55 ndmpd.log
-rw-r--r--@ 2 polinchen  staff     5878  2 25 00:18 notifyd.log
-rw-r--r--@ 2 polinchen  staff    39822  2 25 00:14 perfstatd.log
-rw-r--r--@ 2 polinchen  staff        0  2 24 21:55 php-fpm.error.log
-rw-r--r--@ 2 polinchen  staff        0  2 24 21:55 pipd.log
-rw-r--r--@ 2 polinchen  staff        0  2 24 21:55 secd.log
-rw-r--r--@ 2 polinchen  staff     1797  2 25 00:14 servprocd.log
-rw-r--r--@ 2 polinchen  staff     5107  2 25 00:01 sktlogd.log
-rw-r--r--@ 1 polinchen  staff  3146994  2 22 02:51 spdebug-old.log
-rw-r--r--@ 1 polinchen  staff  2752277  2 25 00:14 spdebug.log
-rw-r--r--@ 2 polinchen  staff        0  2 24 21:55 spmd.log
-rw-r--r--@ 2 polinchen  staff      336  2 24 23:36 vifmgr.log
-rw-r--r--@ 2 polinchen  staff        0  2 24 21:55 vldb.log
-rw-r--r--@ 2 polinchen  staff      662  2 24 23:41 vserverdr.log
-rw-r--r--@ 2 polinchen  staff        0  2 24 21:55 ypbind.log
```

### apache: 意義不大， 讀取SP 的紀錄

```
➜  mlog ls -al apache*
-rw-r--r--@ 2 polinchen  staff  22451  2 19 00:25 apache_access.log
-rw-r--r--@ 2 polinchen  staff  22451  2 19 00:25 apache_access.log.0000000001
-rw-r--r--@ 2 polinchen  staff  26660  1 10  2016 apache_error.log
-rw-r--r--@ 2 polinchen  staff  26660  1 10  2016 apache_error.log.0000000001
```

### memsnap-coresegd.log : 類似top 的命令， 可以看出loading, 但是只有保存一次


```
last pid:  3993;  load averages:  0.74,  1.28,  0.66  up 0+00:05:43    21:28:47
235 processes: 5 running, 230 sleeping

Mem: 266M Active, 357M Inact, 127M Wired, 8204K Cache, 7520K Buf, 19M Free
Swap: 2048M Total, 2048M Free


  PID USERNAME     THR PRI NICE   SIZE    RES STATE   C   TIME   WCPU COMMAND
 3902 root           3  97    0   168M 38588K select  0   0:01 74.00% ndmpd
 3928 root           5  97    0   156M 41600K ucond   0   0:01 63.00% cshmd
 3908 root           5  97    0   153M 41368K ucond   1   0:01 62.00% shmd
 3914 root           4  97    0   154M 42120K select  0   0:01 61.00% schmd
 3922 root           4  97    0   153M 41244K select  0   0:01 57.00% cphmd
 3934 root          15  97    0   144M 37636K ucond   0   0:01 57.00% fpolicy
```

### message 的操作命令， 可以看到操作記錄

```
00000037.00abf378 16ec2006 Sat Feb 25 2017 00:16:27 +08:00 [local2_sudo:notice] root : TTY=unknown ; PWD=/ ; USER=root ; COMMAND=/sbin/vcontext -v 4294967293 /sbin/ping -i0.2 -n -c5 -S169.254.72.8 169.254.182.115
00000037.00abf379 16ec202e Sat Feb 25 2017 00:16:31 +08:00 [local2_sudo:notice] root : TTY=unknown ; PWD=/ ; USER=root ; COMMAND=/sbin/vcontext -v 4294967293 /sbin/ping -i0.2 -n -c5 -s8972 -S169.254.72.8 -D 169.254.182.115
00000037.00abf37a 16ec2056 Sat Feb 25 2017 00:16:35 +08:00 [local2_sudo:notice] root : TTY=unknown ; PWD=/ ; USER=root ; COMMAND=/sbin/vcontext -v 4294967293 /sbin/ping -i0.2 -n -c5 -S169.254.72.8 169.254.152.217
00000037.00abf37b 16ec207e Sat Feb 25 2017 00:16:39 +08:00 [local2_sudo:notice] root : TTY=unknown ; PWD=/ ; USER=root ; COMMAND=/sbin/vcontext -v 4294967293 /sbin/ping -i0.2 -n -c5 -s8972 -S169.254.72.8 -D 169.254.152.217
00000037.00abf37c 16ec21e9 Sat Feb 25 2017 00:17:15 +08:00 [daemon_xinetd:info:4411] START: ssh-systemshell pid=11991 from=169.254.182.115 vsid=-3 role=0x4
00000037.00abf37d 16ec21e9 Sat Feb 25 2017 00:17:15 +08:00 [auth_sshd:error:11991] NSLIBC: __res_nsend(), ../../../../../lib/libc/resolv/res_send.c:456, Vsid = -1 No name servers or res_init() failure. Error: No such process
00000037.00abf37e 16ec21e9 Sat Feb 25 2017 00:17:15 +08:00 [auth_sshd:info:11991] Accepted publickey for diag from 169.254.182.115 port 20566 ssh2
00000037.00abf37f 16ec21e9 Sat Feb 25 2017 00:17:15 +08:00 [local2_sudo:notice] diag : TTY=pts/0 ; PWD=/var/home/diag ; USER=root ; COMMAND=/usr/bin/tar -cvzf /mroot/etc/crash/123456789.NetApp-cluster-dr-02_etc-logs.tar.gz --exclude stats /mroot/etc/log
```

### perfstatd.log : 沒有明顯的記錄

## shelflog : DISK 的記錄， troubleshooting 用

## cm_stats_hourly_data.xml

Path: /etc/log/autosupport/201702030000.0.files

```
<asup:ROW col_time_us="36556566964893">
        <timestamp>1485968440</timestamp>
        <object>aggregate</object>
        <instance>n02_fc_aggr0</instance>
        <instance-uuid>bf8a2f08-e0a2-45a5-813c-57e09b7314c0</instance-uuid>
        <counter>cp_read_blocks</counter>
        <value>192250927</value>
</asup:ROW>
<asup:ROW col_time_us="36556566965127">
        <timestamp>1485968440</timestamp>
        <object>aggregate</object>
        <instance>n02_fc_aggr0</instance>
        <instance-uuid>bf8a2f08-e0a2-45a5-813c-57e09b7314c0</instance-uuid>
        <counter>cp_reads</counter>
        <value>17005662</value>
</asup:ROW>
<asup:ROW col_time_us="36556566965268">
        <timestamp>1485968440</timestamp>
        <object>aggregate</object>
        <instance>n02_fc_aggr0</instance>
        <instance-uuid>bf8a2f08-e0a2-45a5-813c-57e09b7314c0</instance-uuid>
        <counter>instance_name</counter>
        <value>n02_fc_aggr0</value>
</asup:ROW>
<asup:ROW col_time_us="36556566965402">
        <timestamp>1485968440</timestamp>
        <object>aggregate</object>
        <instance>n02_fc_aggr0</instance>
        <instance-uuid>bf8a2f08-e0a2-45a5-813c-57e09b7314c0</instance-uuid>
        <counter>instance_uuid</counter>
        <value>bf8a2f08-e0a2-45a5-813c-57e09b7314c0</value>
</asup:ROW>
```

轉換後的參考資料：

- [xml2csv](http://www.watermark-images.com/xml-to-csv-conversion.aspx)
- [xml2csv-desktop](http://www.luxonsoftware.com/converter/xmltocsv)

```
"1485968440","volume","vol_BDS01_02_vote01","8a8f94d7-5473-4fba-8fc3-bca8d88847a4","total_ops","320297649","36556568609927",0
"1485968440","volume","vol_BDS01_02_vote01","8a8f94d7-5473-4fba-8fc3-bca8d88847a4","vserver_name","fcp_svm_dr","36556568610061",0
"1485968440","volume","vol_BDS01_02_vote01","8a8f94d7-5473-4fba-8fc3-bca8d88847a4","vserver_uuid","f9471476-9c30-11e5-948c-00a0985126aa","36556568610198",0
"1485968440","volume","vol_BDS01_02_vote01","8a8f94d7-5473-4fba-8fc3-bca8d88847a4","write_data","72739156480","36556568610337",0
"1485968440","volume","vol_BDS01_02_vote01","8a8f94d7-5473-4fba-8fc3-bca8d88847a4","write_latency","69328877994","36556568610482",0
"1485968440","volume","vol_BDS01_02_vote01","8a8f94d7-5473-4fba-8fc3-bca8d88847a4","write_ops","70220563","36556568610627",0
"1485968440","volume","vol_BDS01_02_vote02","d655a9d4-c91f-4a84-ba44-f38e5ba4d0c8","avg_latency","78693114782","36556568610925",0
"1485968440","volume","vol_BDS01_02_vote02","d655a9d4-c91f-4a84-ba44-f38e5ba4d0c8","batched_free_log_cap","2.00%","36556568611068",0
"1485968440","volume","vol_BDS01_02_vote02","d655a9d4-c91f-4a84-ba44-f38e5ba4d0c8","instance_name","vol_BDS01_02_vote02","36556568611208",0
```


## CLI command 的輸出方式

```
fas3240> netstat -?
usage: netstat [-anMB]
       netstat -m
       netstat -r [-sn]
       netstat -g
       netstat {-i | -I interface} [-dn] [-w interval] [-f wide|normal] [-x]
       netstat -s [-p protocol]
       netstat -T
```

### 參考資料

- [Interpreting sysstat output](http://community.netapp.com/t5/FAS-and-V-Series-Storage-Systems-Discussions/Interpreting-sysstat-output/td-p/66181)

- [get data from powershell](http://community.netapp.com/t5/Virtualization-and-Cloud-Articles-and-Resources/Data-ONTAP-PowerShell-Toolkit-Collect-SYSSTAT-type-of-information-in-CSV-format/ta-p/86002)

```
PS C:\@work\Scripts> .\Get-NaSysStat.ps1 -NaIP 10.58.97.11 -NaUS root -NaPW <password> -Output Perf.csv -Interval 1
Name                                 Value
----                                     -----
Time                                  4/7/2011 4:37:03 PM
system_model                    FAS6070
ontap_version                     NetApp Release 8.0.1RC2 7-Mode: Thu Oct 21 01:27:45 PDT 2010
serial_no                            ***
system_id                          ***
hostname                           Array-01
nfs_ops                              0.00
cifs_ops                             0.00
http_ops                             0.00
fcp_ops                              8.50
iscsi_ops                           0.00
read_ops                           0.00
sys_read_latency               0.00
write_ops                           8.50
sys_write_latency               0.32
total_ops                            8.50
sys_avg_latency                 0.32
net_data_recv                     2.20
net_data_sent                    9.25
disk_data_read                  169.61
disk_data_written               584.21
cpu_busy                          2.12
avg_processor_busy          1.49
total_processor_busy         5.98
num_processors                4
*********************************************************************
```

[Redirect output of statit](http://community.netapp.com/t5/Data-ONTAP-Discussions/Redirect-output-of-statit/td-p/11970)

To redirect the ouptut to file from some other unix host.
 
a.) setup secure passwordless ssh or rsh between unix host and netapp filer.
 
b.) then run ssh "filer hostname" "priv set advanced; statit -b" { " " quotes are necessary run it for 10 seconds at least}
Then run

```
    ssh "filer hostname" "priv set advanced; statit -e" > file.txt {to end it and redirect to a file}
```
 

3. Is there any tool to understand the output of statit?
 
statit output is very simple. I don't know much about the tool to understand that

### get the statit

[NetApp Statit Command](https://www.bytesizedalex.com/netapp-statit-command/)

```
FILER01> priv set advanced
Warning: These advanced commands are potentially dangerous; use
          them only when directed to do so by NetApp
          personnel.
```

```
FILER04*>statit -e

Hostname: Filer4  ID: 01234567891  Memory: 2862 MB
  NetApp Release 8.1.2P3 7-Mode: Wed Feb 20 19:56:15 PST 2013
    <5O>
  Start time: Thu Jul 30 10:52:33 BST 2015

                       CPU Statistics
     784.181888 time (seconds)       100 %
     689.103174 system time           88 %
      22.282110 rupt time              3 %   (10779740 rupts x 2 usec/rupt)
     666.821064 non-rupt system time  85 %
     879.260600 idle time            112 %

     657.598533 time in CP            84 %   100 %
      18.613492 rupt time in CP                3 %   (8927320 rupts x 2 usec/rupt)

```
   

### 取得log的方式

[Netapp Perfstat](http://www.sysadmintutorials.com/tutorials/netapp/netapp-perfstat-collecting-performance-and-statistics/)

[perfstat tools video](https://www.youtube.com/watch?v=ADzgqUGD2zA)

![perfstat](http://www.sysadmintutorials.com/files/2015/09/perfstatgui.jpg)

[ssh 手動設定流程](https://www.youtube.com/watch?v=ADzgqUGD2zA)

rsh filername sysstat 1 > filer.log

[說明文件1](https://kb.netapp.com/support/s/article/ka31A00000011HiQAI/how-to-redirect-sysstat-output-information-to-a-file?language=ja)

[說明文件2](https://kb.netapp.com/support/s/article/ka31A0000000kIMQAY/how-to-configure-and-enable-remote-shell-rsh-access-on-a-storage-system?language=ja)

