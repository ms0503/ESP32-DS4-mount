ESP32-DS4マウンタ
===============
- [English](README.md)

ESP32-DS4マウンタはESP32-DevKitCとDF1Bコネクタを接続する下駄基板です。

# インターフェース
## UART(送信専用)
DF1Bコネクタには送信専用UARTが接続されており、ESP32への5V供給も兼務しています。
コネクタの3番ピンにESP32のGPIO 33番が接続されています。

# ライブラリ
この基板は一部のシンボル・フットプリントに[kicad-mecha](https://github.com/ms0503/kicad-mecha.git)を使用しています。
別途インポートした上でご利用下さい。

ESP32-DS4のファームウェアは[こちら](https://github.com/ms0503/ESP32-DS4)です。
ESP32-DS4のドライバは[こちら](https://github.com/ms0503/ESP32-DS4-driver)です。

# 設計者
Sora Tonami <[ms0503@outlook.com](mailto:ms0503@outlook.com)>

# ライセンス
この基板のデータは[MITライセンス](LICENSE.md)の下に公開されます。ご自由に改変・再配布して頂いて構いません。

