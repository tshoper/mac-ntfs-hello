update on 2015-05-17

貌似Yosemite更新到10.10.3之后，无论是mount\_ntfs命令还是mount命令，都不能以rw权限挂载NTFS驱动器了。

:(

# mac-ntfs-hello
Mac OS X平台以读写权限挂载NTFS驱动器

## 用途

Mac上插入NTFS格式的移动硬盘默认挂载只能读，不能写

这个程序脚本将NTFS驱动器的系统默认挂载点卸载，以rw权限重新挂载

## 用法

* 插入NTFS移动硬盘到你的Mac

* 打开Terminal.app，下载mac-ntfs-hello.sh，运行

`sudo sh ./mac-ntfs-hello.sh`

* 去/var/Volumes/里查看吧，Finder -> 前往 -> 前往文件夹 -> 输入"/var/Volumes/"

