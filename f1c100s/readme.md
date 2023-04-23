# 全志 F1C100s

## LicheePi Nano

Sipeed 开发板。

短接 E4 和 E5 引脚中间的 spi flash cs引脚和 GND 通电就启用 USB FEL 模式，此时可能无法识别设备，使用 Zadig 装驱动。

```bat
@rem 查看 FEL 设备
sunxi-fel ver
```

## 工具

### [Zadig](https://github.com/pbatard/libwdi/releases)
