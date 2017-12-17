linux 误删的文件，可以通过ext3grep方法或extundelte方法进行恢复。这里仅就extundelete方法进行记录.

1）下载工具extundelete：
```
sudo apt-get install extundelete
```

2)使用方法
详细的使用方法见extundelete -help命令查看。下面结合实例说明用法：

我们知道当我们不小心删除了有用的文件，我们一般是比较容易知道删除的时间的，因此，使用时间这个option可以很快并且精确的恢复出我们想要的文件。那这个dtime怎么生成。请参考如下命令：
