tune2fs
=====================================

简介
^^^^
调整ext系列文件系统的参数

选项
^^^^

* -c 最大挂载次数，超过就要用e2fsck检查
* -C 设置挂载次数
* -e 出错后的操作，继续，重新以只读模式挂载还是崩溃
* -E 文件系统扩展选项
* -f 强制执行
* -g 可以使用保留块的组
* -i 两次检查的最大时间间隔
* -j/J 添加ext3日志以及相关选项
* -l 查看超级块的内容
* -L 设置卷标
* -m 保留块的百分比
* -M 上次挂载的目录
* -o 挂载参数
* -O 文件系统特性管理
* -r 保留块数目
* -q quota的相关设置

示例
^^^^

查看分区信息::

    tune2fs -l /dev/sda1
