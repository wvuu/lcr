mke2fs
=====================================

简介
^^^^
创建ext2/ext3/ext4文件系统，默认配置在/etc/mke2fs.conf，相关命令有mkfs{,.ex{2,3,4}}

选项
^^^^

* -b 块大小
* -c 检查坏块
* -E 文件系统扩展参数
* -F 强制创建文件系统
* -g 每组的block数
* -G 组数
* -i bytes/inode率
* -I 一个inode的大小
* -j 创建journal
* -l 从文件读取坏块列表
* -L 卷标
* -m 保留块的比率
* -M 设置上次挂在目录
* -n 不实际执行，仅显示过程
* -N inode数
* -O 特性列表
* -q 静默执行
* -S 仅写超级块和组信息
* -t 文件系统类型
* -T 使用类型以便命令选择参数
* -U 以制定UUID来创建文件系统


示例
^^^^

格式磁盘::

    mke2fs -j /dev/sda1
