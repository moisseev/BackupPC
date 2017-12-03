BackupPC
========

This is an **unofficial** repository for bug fixes and additional features that for some reason was not (or was not intended to be) merged into [backuppc/backuppc](https://github.com/backuppc/backuppc) repository.

>---
>### For opening issues and pull-requests please visit [backuppc/backuppc](https://github.com/backuppc/backuppc) 
>---

Branches description
========

_Feature branches_    
**cgi-file-size-v3** - Adds $Conf{CgiDateFormatMMDD} that allows set file size format in the backup browse table.    
**pool-graphs-v3** - Adds pool graphs to the status page. Even though it is an optional part of FreeBSD port sysutils/backuppc since Apr 2013, this feature should be considered experimental. Since the graphs has never been included in BackupPC v3 distribution, RRD format was changed in BackupPC v4 and there is no migratrion tool for RRD.
