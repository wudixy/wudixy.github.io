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

   



#尚未找到对应关系日志
SnapMirror: /etc/log/snapmirror
FlexClone: /etc/log/clone
Deduplication: /etc/log/sis
LACP: /etc/log/lacp_log
Backup: /etc/log/backup and /etc/log/ndmpdlog
FTP: /etc/log/ftp.cmd and /etc/log/ftp.xfer
Shelf Messages: /etc/log/shelflog/shelflogata and /etc/log/shelflogesh
Volume Operations: /etc/log/vol_history
Crash Files: /etc/log/crash/aggregates/
Performance Archives: /etc/log/stats/archives
ACP: /etc/log/acp/acplog_master and /etc/log/acplog
