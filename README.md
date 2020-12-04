# Robosys_devicedriver
ロボットシステム学課題1

# DEMO
##デモ動画
https://youtu.be/nBa3PO-qXyA
##回路
![IMG_8974](https://user-images.githubusercontent.com/68839397/101142421-eca21800-3658-11eb-9dba-7a7e71e501b1.jpg)
- LEDはアノードをGPIO25，カソードをGNDに接続する．
# Features
講義通りのコードでLEDを点灯させた．

# Requirement
## 環境
- OS: Ubuntu 20.04.1 LTS

## 道具
- RaspberryPi 3 Model B
- LED
- ジャンパーピン * 3
- ブレッドボード
- 抵抗 100[Ω]

# Usage

```
$git clone https://github.com/Kentotomi/Robosys_devicedriver.git
$cd Robosys_devicedriver
$make
$sudo insmod myled.ko
$sudo chmod 666 /dev/myled0
$echo 1 > /dev/myled0//点灯
$echo 0 > /dev/myled0//消灯
```
# License
"myled.c" is under [GNU General Public License](https://ja.wikipedia.org/wiki/GNU_General_Public_License)
