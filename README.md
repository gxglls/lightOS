# lightOS
一个实现了 bootloader/保护模式/用户进程/内存管理/进程调度切换/特权级隔离等基础功能 的操作系统内核

## 运行方式
1.安装bochs(一个调试友好的X86模拟器), 建议使用版本: 2.6.2
  http://bochs.sourceforge.net/
 
2.使用boch.conf作为配置文件运行bochs
```bash
  ./bochs -f boch.conf
```
3.选择6运行bochs<br>
![](https://github.com/gxglls/lightOS/blob/master/png/bochstart.png)

4.运行bochs后默认是进入调试模式，此时按c直接运行操作系统<br>
![](https://github.com/gxglls/lightOS/blob/master/png/bochscontinue.png)

5.运行结果如下<br>
![](https://github.com/gxglls/lightOS/blob/master/png/osstart.png)

### 如果对实现方式和代码感兴趣，可私聊我，QQ 498340080
