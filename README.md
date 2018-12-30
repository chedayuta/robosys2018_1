# robosys2018_1
ロボットシステム学 課題1 

Raspberry Pi 3 Model B+ 

LEDを3個をGPIO24、GPIO25、GPIO26で制御

# 操作方法
echo 1 > /dev/myled0　　　　
//ピン24(左)を点灯

echo 2 > /dev/myled0　　　　
//ピン25(中央)を点灯

echo 3 > /dev/myled0　　　　
//ピン26(右)を点灯

echo 4 > /dev/myled0　　　　
//全点灯


echo 7 > /dev/myled0　　　　
//ピン24(左)を消灯

echo 8 > /dev/myled0　　　　
//ピン25(中央)を消灯

echo 9 > /dev/myled0　　　　
//ピン26(右)を消灯

echo 0 > /dev/myled0　　　　
//全消灯
