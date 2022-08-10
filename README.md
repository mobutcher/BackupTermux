cd termux Root Directory

`cd /data/data/com.termux/files`


Backup config termux-backup.tar.gz

`tar -zcf /sdcard/termux-backup.tar.gz home usr`


Restore, ensure that the previous backup Home USR directory is in a backup file, pay attention to the backup file will cover the existing configuration
Make sure you have obtained the storage access permissions, and then enter the Termux root directory.

`cd /data/data/com.termux/files`


Refreshing the content before

`tar -zxf /sdcard/termux-backup.tar.gz --recursive-unlink --preserve-permissions`

Restart Termux after the operation is completed
