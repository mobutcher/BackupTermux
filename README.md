termux根目录下<br>
<pre>cd /data/data/com.termux/files</pre><br>

备份配置文件为termux-backup.tar.gz<br>
<pre>tar -zcf /sdcard/termux-backup.tar.gz home usr<pre><br>


恢复，确保之前备份的home usr目录在一个备份文件中，注意 备份文件会覆盖现有配置<br>
确保已经获得存储访问权限，然后进入termux根目录下<br>
<pre>cd /data/data/com.termux/files</pre><br>


解压之前备份的内容
<pre>tar -zxf /sdcard/termux-backup.tar.gz --recursive-unlink --preserve-permissions</pre><br>

操作完成后重启termux

