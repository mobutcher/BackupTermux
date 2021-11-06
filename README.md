termux根目录下
cd /data/data/com.termux/files

备份配置文件为termux-backup.tar.gz
tar -zcf /sdcard/termux-backup.tar.gz home usr

恢复，确保之前备份的home usr目录在一个备份文件中，注意 备份文件会覆盖现有配置
确保已经获得存储访问权限，然后进入termux根目录下
cd /data/data/com.termux/files

解压之前备份的内容
tar -zxf /sdcard/termux-backup.tar.gz --recursive-unlink --preserve-permissions

操作完成后重启termux

