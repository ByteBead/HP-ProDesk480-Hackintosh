# HP ProDesk 480_RX550_Hacintosh

## 电脑配置

|   规格   |                   详细信息                   |
| :------: | :------------------------------------------: |
| 电脑型号 |                HP ProDesk 480                |
| 操作系统 |        macOS   `Big Sur` / `Monterey`        |
|  处理器  |             英特尔 酷睿 i5-10500             |
|   内存   |             镁光 8 GB  DDR4 * 1              |
|  硬盘1   |            PLEXTOR PX-512M9PGN +             |
|  硬盘2   |              SATA 机械硬盘               |
|   显卡   |           自行添加了一块显卡RX550            |
| 无线网卡 | m.2 NGFF插槽 默认出厂为无 已更换为BCM94360CD |
|   声卡   |                   ALC 3205                   |

## 参考与致谢

​	**特别感谢**[黑果小兵](https://blog.daliansky.net) 提供了可参考的EFI文件

## 修改的地方

​	使用了正确的声卡注入ID

​	屏蔽了开机时的RTC校验 Kernel-Quirks-DisableRtcChecksum-ON

​	完全支持VDA解码器，使用核显辅助独显硬解加速	
