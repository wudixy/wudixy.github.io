---
layout: post
title: "NETAPP存储设备日志分析"
categories: [技术资料]
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
