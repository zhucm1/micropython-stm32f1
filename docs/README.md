# Micropython-STM32-STM32F103

在linux上安裝  
sudo apt-get install gcc-arm-none-eabi  
sudo apt-get install gcc  

打开cmd  
切换到目录ports/stm32  
make BOARD=F103  

目前功能  
pyb.freq() ok  
switch ok  
timer ok  
timer pwm ok  
led ok  
rtc ok  
dac ok  
adc ok  
extint ok  
pin ok  
uart ok  
spi ok  
i2c ok  
sdcard ok  
usb MSC ok  
usb cdc ok 需要开放DTR  
can not test  


目前问题  
有些外设使用DMA会有问题  
i2c 使用dma会重放  
