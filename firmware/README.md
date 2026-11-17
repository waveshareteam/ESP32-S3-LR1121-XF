# Firmware

| File | Purpose | Flash offset |
| --- | --- | --- |
| [ESP32-S3-LR1121-XF_FactoryOnly_20260313.bin](ESP32-S3-LR1121-XF_FactoryOnly_20260313.bin) | Factory firmware (2026-03-13) | `0x0` |
| [meshtastic-usart.bin](meshtastic-usart.bin) | Meshtastic firmware (USART) | `0x0` |

```sh
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-LR1121-XF_FactoryOnly_20260313.bin
```
