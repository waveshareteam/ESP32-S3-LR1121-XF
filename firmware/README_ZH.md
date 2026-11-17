# 固件

| 文件 | 用途 | 烧录偏移 |
| --- | --- | --- |
| [ESP32-S3-LR1121-XF_FactoryOnly_20260313.bin](ESP32-S3-LR1121-XF_FactoryOnly_20260313.bin) | 出厂固件（2026-03-13） | `0x0` |
| [meshtastic-usart.bin](meshtastic-usart.bin) | Meshtastic 固件（USART） | `0x0` |

```sh
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-LR1121-XF_FactoryOnly_20260313.bin
```
