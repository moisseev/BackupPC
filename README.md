BackupPC
========

This is a BackupPC unofficial repository to collect bug fixes and additional features during mainstream developer timeout. Hopefully one day some changes from this repository will be merged into mainstream distribution.

>---
>## Notice
>####For opening issues and pull-requests please visit [backuppc/backuppc](https://github.com/backuppc/backuppc) 
>
>---

Branch descriptions
========

_Main branches_ - bug fixes and new features    
**master-v3**    
**master-v4**

_Feature branches_    
**cgi-file-size-v3** - Adds $Conf{CgiDateFormatMMDD} that allows set file size format in the backup browse table.    
**pool-graphs-v3** - Adds pool graphs to the status page. Even though it is an optional part of FreeBSD port sysutils/backuppc since Apr 2013, this feature should be considered experimental. Since the graphs are not included in BackupPC v3, RRD format may be changed in future BackupPC versions.    
**BackupFullExpire-v3**, **BackupFullExpire-v4** - Change exponential full backup expiry algorithm. Current algorithm has issues with backups loss after modifying configuration settings or making manual backups.    

_Clones of BackupPC source code_    
**mainstream-v3**    
**mainstream-v4**
