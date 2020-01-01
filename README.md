# lightOS
一个实现了 bootloader/保护模式/用户进程/内存管理/进程调度切换/特权级隔离等基础功能 的操作系统内核

## 运行方式
1.安装bochs(一个调试友好的X86模拟器), 建议使用版本: 2.6.2
  http://bochs.sourceforge.net/
 
2.使用boch.conf作为配置文件运行bochs
```bash
  ./bochs -f boch.conf
```
