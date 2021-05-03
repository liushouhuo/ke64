# ke64
windows kernel tools

免责声明:
这只是一个免费的辅助软件, 如果您使用本软件, 给您直接或者间接造成损失、损害, 本人概不负责. 从您使用本软件的一刻起, 将视为您已经接受了本免责声明.

本软件仅限于学习交流，如侵权请在24小时进行删除.

### 驱动页面菜单导入导出功能暂未添加，文件页面菜单几个功能暂未添加，下个版本在加，偷个懒



ke64是一个免费但功能强大的内核研究工具。它支持从Windows 7(7601)到Windows 10(19042)，仅支持x64位系统，请在虚拟机运行。

签名：
我没有数字证书，使用HT SRL泄漏的数字证书来签署ke64的驱动程序。使用HT SRL数字证书防病毒软件都认为文件是恶意软件,请大家放心使用

1. 进程,线程,模块,窗口,内存,定时器,热键,消息钩子,事件钩子,inline hook检测,(程序入口反汇编和汇编(双击汇编))
2. 驱动模块
3. FilterDriver(File,Disk,RAW,Volume,Keyboard,Mouse,I8042prt，Tdx,NDIS,PnpManager)
4. CreateProcess,LoadImage,CreateThread,CmpCallback,Shutdown
5. Callbak,ObjectType,ObjectTypeHook,DPC,WFPCallout,minifilter,WorkerThread(堆栈回溯)
6. IRP(Keyboard,Mouse,I8042prt,ndis,nsiproxy,tcpip,partmgr,disk,ntfs,scsi,npfs,fltmgr)
7. GDI,IDT
8. 端口查看
9. 启动项
10. 服务
11. 文件管理
12. 应用层和驱动层(支持反汇编和汇编内存)
13. 功能(...)

# Screenshots
仅在该页面上放置了一张图片。
![image](https://github.com/alinml/ke64/blob/main/screenshots/2.jpg)
