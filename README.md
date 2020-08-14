# M5GOBaseLite

<img src="https://github.com/akita11/M5GOBaseLite/blob/master/M5GOBaseLite1.jpg" width="240px">

<img src="https://github.com/akita11/M5GOBaseLite/blob/master/M5GOBaseLite2.jpg" width="240px">

M5Stackの上部本体(Core)にとりつけて、以下のようなM5GO/Fireの機能やそれ以外の機能を追加できる底板（ベースボード）用の拡張基板です。
- Groveコネクタ(PortA(2個), PortB, PortC, PortD, PortE)（PortA/B/CはM5Stack純正のものと同等です。PortD/EはM5Stack純正品にはありませんが、UI Flowで使用することができるポートです）
- 左右5個ずつのNeoPixel (SK6812)
- LiPoバッテリ接続端子

# 使い方
1. M5Stackの本体(Core、底板を外した状態)に本ボードを差し込みます。
2. M5Stackのプログラムから、Groveコネクタに接続したセンサ類や左右のNeoPixelを使用します。
   - 左右のNeoPixelの制御信号はGPIO15につながっています。UI Flowでは、Hardware→RGB LED、から使用できます
   - 各Groveコネクタのピン配置は以下の通り（中央寄りのVDDから近い側、遠い側の順）
     - PortA: GPIO21(SDA), GPIO22(SCL)
     - PortB: GPIO26, GPIO36
     - PortC: GPIO17(TXD2), GPIO16(RXD2)
     - PortD: GPIO35, GPIO34
     - PortA: GPIO13, GPIO5

# 底面カバー

M5GOBaseLite_cover.svgを厚さ5mmのアクリル板等でカットすると、底面カバーにできます。

<img src="https://github.com/akita11/M5GOBaseLite/blob/master/M5GOBaseLite_cover1.jpg" width="240px">
<img src="https://github.com/akita11/M5GOBaseLite/blob/master/M5GOBaseLite_cover2.jpg" width="240px">



# Author

Junichi Akita (@akita11, akita@ifdl.jp)


