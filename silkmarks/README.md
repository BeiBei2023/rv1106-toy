# PCB 丝印标识（silkmarks）

黑白矢量 SVG，直接导入嘉立创EDA/立创EDA 丝印层（Top Silk/Bottom Silk）。
黑色 = 丝印油墨，白色 = 无油墨（板底色）。

## 文件说明

| 文件 | 用途 | 建议尺寸 |
|------|------|----------|
| 01-board-name.svg | 板名 `RV1106-TOY` | 宽 ≥ 25mm |
| 02-version.svg | 版本 `V0.1 2026` | 宽 ≥ 12mm |
| 03-pin1-dot.svg | 芯片 Pin1 圆点 | Ø 1~1.5mm |
| 04-power-polarity.svg | 电源 `+ −` 极性 | 高 ≥ 1.5mm |
| 05-warning-triangle.svg | 警告三角（中心可改符号） | 高 ≥ 4mm |
| 06-qr-frame.svg | 二维码四角定位框 | 内框 ≥ 24mm（码 20mm 时） |
| 07-usb-direction.svg | USB 方向示意 | 宽 ≥ 8mm |
| 08-port-labels.svg | 接口文字 `MIC LSPK UART` | 按焊盘删改 |

## 丝印工艺约束（下单前核对）

- 线宽 ≥ 0.15mm，文字线高 ≥ 0.8mm（嘉立创常规能力）
- 黑色实心底面积尽量小，大色块易糊
- 码框 `06` 的框线不要压进二维码静默区
- 预览：`preview.png` 为全部标识拼图

## 二维码（勿与本目录混淆）

正式扫码码在 `../qrcode/`，内容为 Pages 网址，**不可更换**。
