#第71章
##系统调用跟踪

###71.0.1 stace/dtruss

显示当前进程的系统调用(第697页)。比如：

```
# strace df -h

```

Mac OS X 的dtruss也有这个功能。

Cygwin也有strace，但如果我理解正确的话，它只为cygwin环境编译exe文件工作。