# Robosys_devicedriver
ロボットシステム学課題1

# DEMO
デモ動画:

# Features
講義通りのコードでLEDを点灯させた．

# Requirement
##環境
- OS: Ubuntu 20.04.1 LTS

##道具
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
